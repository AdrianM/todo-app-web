# todo-app-web

Deploy with:
zip -r ../todo-web-app.zip .
az webapp deploy --resource-group example-resources --name webapp-node-app-3-56mwbc6j --src-path ../todo-web-app.zip --type zip
