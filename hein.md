
npm install @azure/static-web-apps -g

npm run build
in api ...
func start --javascript
(above shoulkd start api on localhost:7071)

swa start http://localhost:3000 --api-location http://localhost:7071

swa start ./build --api-location http://localhost:7071