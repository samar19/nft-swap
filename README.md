## architecture of the app  
our dapps will have three parts back-end front-end and nft smart contract when the user first uses our app the front-end is loaded in the web browser the front-end sends a request to the smart contract of the nft to know the url of the metadata the metadata of an nft is some extra info that is too big to be stored on blockchain so we only store a pointer of this info on the blockchain the front-end gets this metadata url and with it it sends a request to the backend the backend answers with the metadata of the token that's a json document in this json document 
we also have the url of the image of the nft this image can be stored on any server but in our case that's going to be on the same server as the metadata so our front-end fetches the image from the server and display to the user as well as the metadata

## backend (strapi)
schema 
comments
images
posts

## frontend (next.js)
show all postes 
show all images 
show single post