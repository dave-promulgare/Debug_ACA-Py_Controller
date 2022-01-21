# Debug_ACA-Py_Controller
Simple controller for debugging ACA-Py connections

You will need to set your own IP address for your server that you are running the ACA-Py on in the webhook.js route code.  Otherwise, it does not know where to make the REST Call to your ACA-Py that you are controlling.

Register the IP address for this app in your ACA-Py using the --webhook-url command

--webhook-url http://35.183.106.161:3000
