RedcartClientBridge
===================

Redcart Api PHP Client - https://github.com/ziollek/RedcartClient - bridge for symfony2

## Configuration

Add following lines to your composer.json file (section require):

        require: {
            ...

            "publib/RedcartClient": "dev-master",
            "publib/RedcartClientBridge": "dev-master",
        }


Add following repositories to your composer.json:

        "repositories": [
            {
                "type": "git",
                "url": "https://github.com/ziollek/RedcartClient.git"
            },
            {
                "type": "git",
                "url": "https://github.com/ziollek/RedcartClientBridge.git"
            }
        ]


Add your api key to app/config/parameters.yml as below:

        redcart_api_key: your_api_key

Enjoy!
        