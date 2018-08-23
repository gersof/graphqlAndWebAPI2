# ASP.NET Web Api GraphQL Example

```
> npm install
> npm run webpack
> Run from Visual Studio

Para crear y consultar:

mutation writeHuman ($human:HumanInput!){
  createHuman(human: $human)
  { 
    id
    name 
    homePlanet 
  } 
}
  
query readHuman {
  human(id:"valor que retorne la mutation") {
    id
    name
    homePlanet
  }
}

