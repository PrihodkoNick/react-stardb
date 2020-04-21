getResourse("https://swapi.dev/api/people/13453454345")
  .then((body) => {
    console.log("body:", body);
  })
  .catch((err) => {
    console.log("Could not fetch", err);
  });

fetch("https://swapi.dev/api/people/1")
  .then((res) => {
    return res.json(); // get result
  })
  .then((body) => {
    console.log("body:", body); // get result body
  });