# error_responses

{
  "100": {
    "code": 100,
    "message": "Continue",
    "description": "The server has received the request headers and the client should proceed to send the request body.",
    "suggestedAction": "Continue with the request body transmission."
  },
  "101": {
    "code": 101,
    "message": "Switching Protocols",
    "description": "The requester has asked the server to switch protocols.",
    "suggestedAction": "Follow the new protocol specified in the response."
  },
  "200": {
    "code": 200,
    "message": "OK",
    "description": "The request has succeeded.",
    "suggestedAction": "No specific action required. Request was successful."
  },
  "201": {
    "code": 201,
    "message": "Created",
    "description": "The request has been fulfilled, and a new resource is created.",
    "suggestedAction": "Review the response body for details of the newly created resource."
  },
  "202": {
    "code": 202,
    "message": "Accepted",
    "description": "The request has been accepted for processing, but the processing has not been completed.",
    "suggestedAction": "Check the response headers for updates on the request status."
  },
  "203": {
    "code": 203,
    "message": "Non-Authoritative Information",
    "description": "The server is a transforming proxy that received a 200 OK from its origin, but is returning a modified version of the origin's response.",
    "suggestedAction": "Use the provided information, but consider it non-authoritative."
  },
  "204": {
    "code": 204,
    "message": "No Content",
    "description": "The server successfully processed the request and is not returning any content.",
    "suggestedAction": "No action needed, as the request was processed successfully."
  },
  "205": {
    "code": 205,
    "message": "Reset Content",
    "description": "The server successfully processed the request, but is not returning any content. The client should reset the document view.",
    "suggestedAction": "Reset the document view."
  },
  "206": {
    "code": 206,
    "message": "Partial Content",
    "description": "The server is delivering only part of the resource due to a range header sent by the client.",
    "suggestedAction": "Use the provided partial content as needed."
  },
  "300": {
    "code": 300,
    "message": "Multiple Choices",
    "description": "The requested resource has multiple choices, each with its own specific location.",
    "suggestedAction": "Choose one of the provided choices."
  },
  "301": {
    "code": 301,
    "message": "Moved Permanently",
    "description": "The requested resource has been permanently moved to a new location.",
    "suggestedAction": "Update the URL permanently."
  },
  "302": {
    "code": 302,
    "message": "Found",
    "description": "The requested resource resides temporarily under a different URL.",
    "suggestedAction": "Use the temporary URL provided in the response."
  },
  "303": {
    "code": 303,
    "message": "See Other",
    "description": "The response to the request can be found under a different URL and should be retrieved using a GET method.",
    "suggestedAction": "Issue a GET request to the URL provided in the response."
  },
  "304": {
    "code": 304,
    "message": "Not Modified",
    "description": "The resource has not been modified since the last request specified by the conditional headers (If-Modified-Since or If-None-Match).",
    "suggestedAction": "Use a cached copy of the resource."
  },
  "305": {
    "code": 305,
    "message": "Use Proxy",
    "description": "The requested resource must be accessed through the proxy given by the Location field.",
    "suggestedAction": "Access the resource through the provided proxy."
  },
  "307": {
    "code": 307,
    "message": "Temporary Redirect",
    "description": "The requested resource has been temporarily moved to another URL.",
    "suggestedAction": "Redirect temporarily to the provided URL."
  },
  "308": {
    "code": 308,
    "message": "Permanent Redirect",
    "description": "The requested resource has been permanently moved to another URL.",
    "suggestedAction": "Update the URL permanently."
  },
  "400": {
    "code": 400,
    "message": "Bad Request",
    "description": "The server cannot process the request due to invalid syntax.",
    "suggestedAction": "Please review the request and ensure it follows the correct syntax."
  },
  "401": {
    "code": 401,
    "message": "Unauthorized",
    "description": "The request has not been applied because it lacks valid authentication credentials.",
    "suggestedAction": "Please provide valid credentials or authenticate the request."
  },
  "402": {
    "code": 402,
    "message": "Payment Required",
    "description": "Reserved for future use. Currently, it is not used.",
    "suggestedAction": "N/A"
  },
  "403": {
    "code": 403,
    "message": "Forbidden",
    "description": "The server understood the request, but refuses to authorize it.",
    "suggestedAction": "Check your permissions or contact the system administrator for access."
  },
  "404": {
    "code": 404,
    "message": "Not Found",
    "description": "The server cannot find the requested resource.",
    "suggestedAction": "Verify the URL for any mistakes or contact the server administrator."
  },
  "405": {
    "code": 405,
    "message": "Method Not Allowed",
    "description": "The method specified in the request is not allowed for the resource.",
    "suggestedAction": "Use a different HTTP method for the request."
  },
  "406": {
    "code": 406,
    "message": "Not Acceptable",
    "description": "The resource identified by the request is only capable of generating responses that have unacceptable content characteristics.",
    "suggestedAction": "Modify the request headers to accept content in an acceptable format."
  },
  "407": {
    "code": 407,
    "message": "Proxy Authentication Required",
    "description": "The client must first authenticate itself with the proxy.",
    "suggestedAction": "Provide valid credentials to the proxy server."
  },
  "408": {
    "code": 408,
    "message": "Request Timeout",
    "description": "The server timed out waiting for the request.",
    "suggestedAction": "Please retry the request after a reasonable amount of time."
  },
  "409": {
    "code": 409,
    "message": "Conflict",
    "description": "The request could not be completed due to a conflict with the current state of the resource.",
    "suggestedAction": "Resolve the conflict and resubmit the request."
  },
  "410": {
    "code": 410,
    "message": "Gone",
    "description": "The requested resource is no longer available at the server and no forwarding address is known.",
    "suggestedAction": "Remove the resource reference from the client."
  },
  "411": {
    "code": 411,
    "message": "Length Required",
    "description": "The server refuses to accept the request without a defined Content-Length.",
    "suggestedAction": "Include a Content-Length header in the request."
  },
  "412": {
    "code": 412,
    "message": "Precondition Failed",
    "description": "The server does not meet one of the preconditions specified in the request.",
    "suggestedAction": "Review and correct the preconditions in the request."
  },
  "413": {
    "code": 413,
    "message": "Payload Too Large",
    "description": "The request is larger than the server is willing or able to process.",
    "suggestedAction": "Reduce the request payload size and try again."
  },
  "414": {
    "code": 414,
    "message": "URI Too Long",
    "description": "The URI provided was too long for the server to process.",
    "suggestedAction": "Shorten the URI and resend the request."
  },
  "415": {
    "code": 415,
    "message": "Unsupported Media Type",
    "description": "The server does not support the media type of the request.",
    "suggestedAction": "Ensure the media type of the request is supported by the server."
  },
  "416": {
    "code": 416,
    "message": "Range Not Satisfiable",
    "description": "The client has asked for a portion of the file, but the server cannot supply that portion.",
    "suggestedAction": "Adjust the range request headers and retry the request."
  },
  "417": {
    "code": 417,
    "message": "Expectation Failed",
    "description": "The expectation given in the request's Expect header field could not be met by the server.",
    "suggestedAction": "Review and adjust the expectations specified in the request."
  },
  "418": {
    "code": 418,
    "message": "I'm a teapot",
    "description": "This code was defined in 1998 as one of the traditional IETF April Fools' jokes, in RFC 2324, Hyper Text Coffee Pot Control Protocol.",
    "suggestedAction": "No action needed. This response code is not expected to be encountered in practice."
  },
  "421": {
    "code": 421,
    "message": "Misdirected Request",
    "description": "The request was directed at a server that is not able to produce a response.",
    "suggestedAction": "Redirect the request to a different server."
  },
  "422": {
    "code": 422,
    "message": "Unprocessable Entity",
    "description": "The server understands the content type of the request entity but was unable to process the contained instructions.",
    "suggestedAction": "Review and correct the request entity before resubmitting."
  },
  "423": {
    "code": 423,
    "message": "Locked",
    "description": "The resource that is being accessed is locked.",
    "suggestedAction": "Wait for the resource to be unlocked before retrying the request."
  },
  "424": {
    "code": 424,
    "message": "Failed Dependency",
    "description": "The request failed due to the failure of a previous request.",
    "suggestedAction": "Resolve the dependencies and resubmit the request."
  },
  "425": {
    "code": 425,
    "message": "Too Early",
    "description": "The server is unwilling to risk processing a request that might be replayed.",
    "suggestedAction": "Wait for a period of time before retrying the request."
  },
  "426": {
    "code": 426,
    "message": "Upgrade Required",
    "description": "The client should switch to a different protocol.",
    "suggestedAction": "Upgrade the protocol as required by the server."
  },
  "428": {
    "code": 428,
    "message": "Precondition Required",
    "description": "The server requires the request to be conditional.",
    "suggestedAction": "Include the required preconditions in the request."
  },
  "429": {
    "code": 429,
    "message": "Too Many Requests",
    "description": "The user has sent too many requests in a given amount of time.",
    "suggestedAction": "Limit the frequency of requests or wait for some time before retrying."
  },
  "431": {
    "code": 431,
    "message": "Request Header Fields Too Large",
    "description": "The server is unwilling to process the request because its header fields are too large.",
    "suggestedAction": "Reduce the size of the request headers and retry."
  },
  "451": {
    "code": 451,
    "message": "Unavailable For Legal Reasons",
    "description": "The server is denying access to the resource as a consequence of a legal demand.",
    "suggestedAction": "Contact the service provider for further information."
  },
  "500": {
    "code": 500,
    "message": "Internal Server Error",
    "description": "The server encountered an unexpected condition that prevented it from fulfilling the request.",
    "suggestedAction": "Contact the server administrator or try again later."
  },
  "501": {
    "code": 501,
    "message": "Not Implemented",
    "description": "The server does not support the functionality required to fulfill the request.",
    "suggestedAction": "Contact the service provider for further assistance."
  },
  "502": {
    "code": 502,
    "message": "Bad Gateway",
    "description": "The server received an invalid response from the upstream server.",
    "suggestedAction": "Check the upstream server status or contact the system administrator."
  },
  "503": {
    "code": 503,
    "message": "Service Unavailable",
    "description": "The server is currently unavailable.",
    "suggestedAction": "Please try again later or contact the service provider for assistance."
  },
  "504": {
    "code": 504,
    "message": "Gateway Timeout",
    "description": "The server did not receive a timely response from the upstream server.",
    "suggestedAction": "Check the upstream server status or try again later."
  },
  "505": {
    "code": 505,
    "message": "HTTP Version Not Supported",
    "description": "The server does not support the HTTP protocol version used in the request.",
    "suggestedAction": "Upgrade the HTTP protocol version or contact the service provider for further assistance."
  },
  "506": {
    "code": 506,
    "message": "Variant Also Negotiates",
    "description": "Transparent content negotiation for the request results in a circular reference.",
    "suggestedAction": "Review and adjust the content negotiation settings."
  },
  "507": {
    "code": 507,
    "message": "Insufficient Storage",
    "description": "The server is unable to store the representation needed to complete the request.",
    "suggestedAction": "Free up storage space or contact the system administrator."
  },
  "508": {
    "code": 508,
    "message": "Loop Detected",
    "description": "The server detected an infinite loop while processing the request.",
    "suggestedAction": "Break the loop or modify the request to avoid it."
  },
  "510": {
    "code": 510,
    "message": "Not Extended",
    "description": "Further extensions to the request are required for the server to fulfill it.",
    "suggestedAction": "Include the required extensions in the request."
  },
  "511": {
    "code": 511,
    "message": "Network Authentication Required",
    "description": "The client needs to authenticate to gain network access.",
    "suggestedAction": "Provide valid authentication credentials to gain network access."
  }
}
