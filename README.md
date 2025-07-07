<pre>
# Dependencies-install
How to Install Dependencies and run them for
  > .Net
  -> To add a dependency, run the dotnet package add command
  dotnet package add Microsoft.EntityFrameworkCore
  -> To remove a dependency, run the dotnet package remove command
  dotnet package remove Microsoft.EntityFrameworkCore
 
  > React
  -> Make sure your project has a package.json file defined in it.
  -> Set the The npm command with arguments to run to install.
     npm install
  -> Add the Run npm command Step to your Workflow.
     npm run build

  > Angular
  -> install the dependencies needed using the npm command:
     npm install @angular/service-worker
  -> When the installation is successful, we should see the new package added to the dependencies object in the project's package.json file.

  > Node.js
  -> Installing dependencies
     npm install
  -> Build if using TypeScript
     npm run build
  -> Deploy to server
     scp -r . user@server:/var/www/myapp
   -> When you deploy your function, Cloud Run functions installs dependencies declared in the package.json file using the npm install command:
      npm install --production

  > Java
  -> Build the JAR
     ./mvnw clean package  # or ./gradlew build
  -> will get a JAR in /target or /build/libs -> Deploy
     scp target/myapp.jar user@server:/opt/myapp/
  -> Run
     java -jar myapp.jar

  > Golang
  -> Locating and importing useful packages
  import "rsc.io/quote"
  -> Enabling dependency tracking in your code
     $ go mod init example/mymodule
  -> 
  
  
 

</pre>
