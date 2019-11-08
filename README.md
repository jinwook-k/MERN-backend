# Getting Started

#### Clone this repo
```
git clone https://github.com/JinwookKim/mern-backend-boiler.git
```

#### Configure .env file
Create a `.env` file with these credentials in it. It is not included in this project because it is ignored in the `.gitignore` file.

```base
DB=mongodb+srv://<username>:<password>@<database>-abc12.mongodb.net/test?retryWrites=true&w=majority
jwtSecret=sl_myJwtSecret
```

#### Start the server
```bash
npm run server
```

Code credit goes to: https://github.com/bradtraversy/mern_shopping_list    

**Only difference is using .env instead of a config folder and this repo only includes the backend code.**
