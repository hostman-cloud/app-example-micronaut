An example Micronaut application that can be deployed to Hostman Cloud Apps with no configuration.

🎉 [Demo]

🚀 [Create your App](https://hostman.cloud/my/apps/create)

📚 [Hostman Cloud Apps Documentation](https://hostman.com/docs/app-platform/)

## <a name="dev"></a>Running the project locally

```bash
# install dependencies
./mvnw dependency:resolve

# run in dev mode
./mvnw mn:run

# build for production
./mvnw package && java -jar target/app-example-micronaut-0.1.jar
```
