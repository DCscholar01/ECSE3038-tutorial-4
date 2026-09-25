POST first run 
status code: 201
# of devices: 6

POST second run 
status code: 201
# of devices: 7

PUT FIRST run 
status code: 200
# of devices: 7

PUT second run 
status code: 200
# of devices: 7

DELETE FIRST run 
status code: 200
# of devices: 6

DELETE second run 
status code: 404
# of devices: 6

The DELETE and PUT method left the system in the same state. This is know as Idempotency.