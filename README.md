# wcbreadcrumbsedit
Enlever "Produits Identifiés" sur les breadcrumb woocommerce

/wp-content/plugins/woocommerce/templates/global -> breadcrumb.php

Ajouter un fwrite() pour réécrire le fichier
- substr(substr($crumb[0], 28), 0, -7)
