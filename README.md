# MapUI
- Create web interface using `django`
- Use `leaflet` for implementing the mapGUI
- Create a polygonal area to fetch  `lattitude` and `longitude`  
    - The polygon's area within should include the data as the list of Tower within the created area 
- Create a database with dummy towerdata (`longitude`, `lattitude`, `provincename`, `region`)
- Upon selection or polygon creation on the map, it should show list of Tower's within it

## Web Interface in `Django`

- Create a virtual environment as
```ps
python -v venv myenv 
myenv/Scripts/activate
```
- Install the required dependencies using the `requirements.txt` file
```ps
pip install -r requirements.txt   
```

## `Leaflet` Implementation in `Django`

Use the following command to install django

```ps
pip install django
pip install django-admin
```
Since we are using virtual environment it should already have above within the packages so we use the following command to continue

```ps
django-admin startproject TowerMap
```
Here TowerMap is name of the `Django` project

## Initial Demo 
<video src="../Assets/Map Selector.mp4" loop>
