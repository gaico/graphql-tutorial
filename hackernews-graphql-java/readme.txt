mutation createLink{
  createLink(
    url: "www.practis.com",
    description:"Bestaat allang niet meer"
  ){
    url
    description
  }
}

query allLinks{
  allLinks{
    url
    description
  }
}