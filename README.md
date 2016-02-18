This is a web app to view and manage menus for restaurants.

This app uses the flast framework and sqlalchemy.

Type python project.py to run.

To view menu of a restaurant, use the URL:
localhost:/5000/restaurant_id
Default restaurant_id = 1 will be used if no restaurant_id is provided.

To acquire JSON file for all menu items of a restaurant, use the URL:
localhost:/5000/restaurants/restaurant_id/menu/JSON

For JSON file of one menu item, use the URL:
localhost:/5000/restaurants/restaurant_id/menu/int:menu_id/JSON