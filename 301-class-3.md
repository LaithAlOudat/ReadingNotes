# Lifting State Up
##### Often, several components need to reflect the same changing data. We recommend lifting the shared state up to their closest common ancestor. Let’s see how this works in action.

### Adding a Second Input
##### Our new requirement is that, in addition to a Celsius input, we provide a Fahrenheit input, and they are kept in sync.
##### We have two inputs now, but when you enter the temperature in one of them, the other doesn’t update. This contradicts our requirement: we want to keep them in sync.
##### We also can’t display the BoilingVerdict from Calculator. The Calculator doesn’t know the current temperature because it is hidden inside the TemperatureInput.
##### important Note:
###### There is no special meaning to either temperature or onTemperatureChange prop names in custom components. We could have called them anything else, like name them value and onChange which is a common convention.


# Lists and Keys
##### First, let’s review how you transform lists in JavaScript.


### Rendering Multiple Components
##### You can build collections of elements and include them in JSX using curly braces {}.
#####

### Basic List Component
##### We can refactor the previous example into a component that accepts an array of numbers and outputs a list of elements.
##### When you run this code, you’ll be given a warning that a key should be provided for list items. A “key” is a special string attribute you need to include when creating lists of elements. We’ll discuss why it’s important in the next section.

### Keys
##### Keys help React identify which items have changed, are added, or are removed.
