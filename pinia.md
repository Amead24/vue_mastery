## State management with pinia

### vue component ({})
vue component stores local data in data property (with options API) and ref (with script setup api)

vs. pinia which uses state property

vue component uses methods to update data (aka local state) vs. pinia uses actions to affect state

vue component uses computed to wrap data vs. pinia uses getters for processed state

## modular

pinia allows for many stores (which improves lazy loading because only those stores that are needed are loaded)
each of which don't overlap allows for modularity.

