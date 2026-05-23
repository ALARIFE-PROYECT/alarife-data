# alarife-data
ORM for alarife framework


[object Database]
11. Proxy + computed names

Muy usado en ORMs y frameworks.

function makeEntity(name) {
  return {
    [`find${name}`]() {},
    [`save${name}`]() {}
  };
}
