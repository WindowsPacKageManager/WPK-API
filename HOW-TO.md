# WPK-API
The Windows PacKage Manager API  for add .wpk support in your aplications, Supports Node.js using Node Package Manager (NPM)
This API is Programmed in Node.js and is Easy to Install
in your Node.js Terminal Type  npm install wpk-api
You Installled WPK-API 
# Add This API To Your Project
In Your IDE Create a File called `wpk.js` Type The following Piece of Code

`}
active.wpk create c:/programfiles/myapp //change it for your directory
install.wpk c:/programfiles/myapp file .exe // optional, delete it if you dont want to auto install your package
if install.wpk true then
active.wpk install .wpk > .exe true .wpk transform // transform your .WPK in a .EXE (optional)
end
 end
 `
