# s-config-server
Clone https://github.com/iusverma/s-config with this project and update the path in application.properties to run this project.

# latest code
Check config-vid-yml branch.

# sample uris
- http://localhost:8080/application/default
- http://localhost:8080/product/default
- http://localhost:8080/address/default

# how to add a new yml
Simple add a new yml file in https://github.com/iusverma/s-config project. Url for this new added yml will be
  http://localhost:8080/yml-name/default

  Example: if you add a new yml with name sample.yml
  Uri will be http://localhost:8080/sample/default

# URL for native profile
  http://localhost:8080/person/native
