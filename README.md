# Python Community Map
A map full of lovely Python communities 🐍❤️

*This is not a map for specific events or conferences, but rather for local communities.*

## How to add a new community to the map?
### 1. Fork this repo
First of all, fork this repo :) You can find instructions [here](https://help.github.com/articles/fork-a-repo/) or [here](https://guides.github.com/activities/forking/).

### 2. Add your community
Add your community information to the `communities.yaml` file, with the following structure:
```yaml
- name: GruPy-RP
  lat: -21.176630
  lng: -47.820840
  url: https://www.meetup.com/grupy-rp/
```

If you are adding a new country, add a comment header before the community:
```yaml
###
### Brazil
###
- name: GruPy-RP
  lat: -21.176630
  lng: -47.820840
  url: https://www.meetup.com/grupy-rp/
```

Please, add communities and countries (if necessary) in alphabetical order.

To get the latitude and longitude information, you can use [this](https://www.latlong.net/) site.

### 3. Make a pull request
At the end, create a pull request for this repository! You can find instructions [here](https://help.github.com/articles/creating-a-pull-request/).

## License
[MIT](https://github.com/jonatasbaldin/python-community-map/blob/master/LICENSE).
