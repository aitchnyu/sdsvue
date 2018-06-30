# Vue.js for bug-free interactive web pages

## Exercise 1
 - How to introduce in a page
 - Reactivity and Dev tools
 - Binding data and inputs
 - Methods
 - Fetching data

### Steps
- Install Vue Devtools in Firefox or Chrome
- Open Vue devtools for exercise_1_practice.html
- Click root component
- `$vm0.name = 'Somebody'`
- `randomName(function(name){console.log("name is", name)})`
- Text input - bind to model
- Buttons - bind to method
- `reverse` and `fetchName`

Minified and dev version - size and speed, download
What happens without v-cloak?

### Resources
- Two approaches: https://vuejs.org/v2/guide/installation.html
- Reactivity: https://vuejs.org/v2/guide/reactivity.html
- Losing `this` binding https://stackoverflow.com/questions/20279484/how-to-access-the-correct-this-inside-a-callback?noredirect=1&lq=1

## Excercise 2

- Bootstrap 4
- Usage of components
- Data binding with number
- v-for and :key
- computed properties

### Steps
- Display table entries - bind to numbers
- row color
- addNewItem - just push to array
- total and costliest

### Resources
- Start using Bootstrap in Vue: https://bootstrap-vue.js.org/docs/reference/starter-templates/
- v-for: https://vuejs.org/v2/guide/list.html
- Why use key: https://vuejs.org/v2/guide/list.html#key
- Computed properties: https://vuejs.org/v2/guide/computed.html

## Excercise 3

- Wrapper around popular projects like Leaftet
- references

### Steps
- set center and markers to any of the values
- set zoom
- on zoom and move, show map coordinates
- add center to map

### Resources
- References: https://vuejs.org/v2/api/#vm-refs
