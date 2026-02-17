Vijay Xavier Walter.     
041276252.     
CST8915 Full-stack Cloud-native Development.      
Winter 2026.      

---

## Demo Video

🎥 [Watch Demo Video] (https://youtu.be/52gw2PQV0_8)

Answers for Reflection Questions.

1. moved the RabbitMQ username and password out of the script and into the .env file.
replaced a static connection string with process.env.RABBITMQ_CONNECTION_STRING
configured the app to treat RabbitMQ as an attached resource that is reached via a URL.

2. It is important to use environment variables because they allow to separate code from configuration, making application more secure, portable, and easier to manage across different environments.

3. The 12-Factor methodology states: "One codebase tracked in revision control, many deploys."
By having a separate repository for each microservice, each service becomes its own "app."

Links to the three service repositories created:

order-service - https://github.com/vijayxavierwalter/26W_CST8915_Lab2_order_service.git 

product-service - https://github.com/vijayxavierwalter/26W_CST8915_Lab2_product_service.git   

store-front - https://github.com/vijayxavierwalter/26W_CST8915_Lab1.git   
