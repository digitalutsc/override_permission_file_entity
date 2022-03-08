# Override Private Permission from File Entity with Group module instead

## How to Run

Run the following commands:

````

cd /var/www/html/drupal/web/modules/contrib/file_entity

wget https://github.com/digitalutsc/override_permission_file_entity/blob/main/override_file_access.patch

patch -p1 < override_file_access.patch

````
