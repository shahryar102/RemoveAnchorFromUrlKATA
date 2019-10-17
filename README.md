# RemoveAnchorFromUrlKATA
function removeUrlAnchor(url){
  newUrl=''
  for(i=0;i<url.length;i++){
    if (!(url[i]=='#')){newUrl+=url[i]}
  }
  console.log(newUrl)
  return newUrl
}
removeUrlAnchor("#https://www.yahoo.com")
