# LocationTrackerPrivacyPolicy

Hi there!
This app is a location tracker that fetches your location every 5 seconds to send it to an MQTT broker.
An MQTT subscriber can be listening to that broker to enable MQTT location fetching for a wide variety of apps.
By default, it sends the location to a public broker. But by tapping the mqtt status button on the top left, you can change the broker, port, topic, and client id

The data "collection" is just sending the location to an MQTT broker. This can be changed to a private IP address in the app, but by default is public. The data is not sold or used for any other purpose.
