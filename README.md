# nothing..name": "Fallen Robot",

      "description": "Telegram Group Management Bot.",

      "logo": "https://te.legra.ph/file/72e135da30a1a349f2844.jpg",

      "keywords": [

         "telegram",

         "modular",

         "group",

         "manager",

         "Fallen"

      ],   

   "repository": "https://github.com/AnonymousX1025/FallenRobot",

   "stack": "heroku-22",

   "addons": [

      {

         "options": {

            "version": "12"

         },

         "plan": "heroku-postgresql"

      }

   ],

   "env": {

      "API_ID": {

         "description": "Get this value from my.telegram.org/apps.",

         "required": true,

         "value": ""

      },

      "API_HASH": {

         "description": "Get this value from my.telegram.org/apps.",

         "required": true,

         "value": ""

      },

      "ALLOW_EXCL": {

         "description": "Set this to True if you want ! to be a command prefix along with /. Recommended is True",

         "value": "True"

      },

      "CASH_API_KEY": {

         "description": "Required for currency converter. Get yours from https://www.alphavantage.co/support/#api-key",

         "required": true,

         "value": ""

      },

      "DEL_CMDS": {

         "description": "Set this to True if you want to delete command messages from users who don't have the perms to run that command.",

         "value": "True"

      },

      "ENV": {

         "description": "Setting this to ANYTHING will enable environment variables. Leave it as it is",

         "required": true,

         "value": "True"

      },

      "EVENT_LOGS": {

         "description": "Event logs channel to note down important bot level events, recommend to make this public. ex: '-123456'",

         "required": true,

         "value": ""

      },

      "MONGO_DB_URI": {

         "description": "Required for database connections.",

         "required": true,

         "value": ""

      },

      "OWNER_ID": {

         "description": "Your user ID as an integer.",

         "required": true,

         "value": "1356469075"

      },

      "START_IMG": {

         "description": "Telegraph link of the image which will be shown at start command.",

         "required": true,

         "value": ""

      },

      "SUPPORT_CHAT": {

         "description": "Your Telegram support group chat username where your users will go and bother you with shit But be like: MyGroupChatUsernameBlah. If this ever points to Fallen Support than consider you made an enemy.",

         "required": true,

         "value": "DevilsHeavenMF"

      },

      "TIME_API_KEY": {

         "description": "Required for timezone information. Get yours from https://timezonedb.com/api",

         "required": true,

         "value": ""

      },

      "TOKEN": {

         "description": "Get bot token from @BotFather on TG",

         "required": true,

         "value": ""

      }

   }

}
