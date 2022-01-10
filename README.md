# How to use

After you run `amplify add function`, navigate to src directory using terminal, and then run the following command: 

     rm index.js package.json event.json \
     git clone https://github.com/hackmajoris/amplify-ts-lambda-skeleton.git && \
     cp -r amplify-ts-lambda-skeleton/{.,}* ./ && rm -rf amplify-ts-lambda-skeleton && \
     rm -rf .git README.md && \
     npm install && npm run-script tsc 

After the success execution, open `package.json` and change the name of the function to the name of your function at the `amplify:<LAMBDA_NAME>`action (make sure that you change also the path).
