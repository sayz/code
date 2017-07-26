###Simple HTTP server supporting SSL secure communications

Originally published: 2005-10-22 10:01:32
Last updated: 2008-08-02 16:04:56
Author: Sebastien Martini

This recipe describes how to set up a simple HTTP server supporting SSL secure communications. It extends the SimpleHTTPServer standard module to support the SSL protocol. With this recipe, only the server is authenticated while the client remains unauthenticated (i.e. the server will not request a client certificate). Thus, the client (typically the browser) will be able to verify the server identity and secure its communications with the server.