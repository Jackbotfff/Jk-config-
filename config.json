from fastapi import FastAPI
from fastapi.responses import JSONResponse

app = FastAPI()

@app.get("/config")
def config():
    data = {
        "enableLogin": False,
        "loginIcon": "JKMODZ",
        "loginTitle": "Version : 20",
        "loginHint": "key",
        "loginButtonText": "login !!",
        "invalidKeyRedirect": "",
        "validKeys": ["JACK","JACK"],
        "appIcon": "V15",
        "bgColor": "#ff00b7ff",
        "accentColor": "#ff00b7ff",
        "btnColor": "#ff00b7ff",
        "btnTextColor": "#ff00b7ff",
        "continueText": "CONTINUE",
        "autoRedirect": True,
        "redirectUrl": "",
        "socialButtons": [{"type":"","url":""},{"type":"","url":""}],
        "versionInfo": {
            "latestVersion": "16.0.0",
            "title": "Official Announcement",
            "message": "هنا دير copy كامل ديال message",
            "downloadUrl": "",
            "forceUpdate": False,
            "showDiscordButton": True,
            "downloadButtonText": "Coming Soon!",
            "discordButtonText": "Get Support",
            "laterButtonText": "Remind Me Later"
        }
    }
    return JSONResponse(content=data)