# Running wordpress

```
$ docker compose up
```

Goto `http://localhost:8080/` for the public site, and `http://localhost:8080/wp-admin` for the admin site.

# Creating the WP theme zip

```
$ cd ..
$ zip poc-wp-gobusiness.zip poc-wp-gobusiness
```

# Install the theme

Goto `http://localhost:8080/wp-admin/themes.php` > Add New > Upload Theme. Choose the file and click Install Now. Then click Activate.

Goto `http://localhost:8080/` to verify.