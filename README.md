# Monkey Catalog

Forked from rancher/charts for Rancher 2.x

## Add Catalog in Rancher 2.x

- From the Global view, choose Catalogs from the main menu.
- Click Add Catalog.
- Complete the form with "Monkey-catalog"	and "https://github.com/monkey-company/charts.git"

## Add Catalog from terminal

```
helm repo add monkey-catalog https://github.com/monkey-company/charts.git
helm search monkey-catalog
```

Enjoy !
