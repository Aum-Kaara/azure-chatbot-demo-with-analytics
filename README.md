# azure-chatbot-demo-with-analytics
azure-chatbot-demo-with-analytics

# How to log Custom Events
```
var properties = new Dictionary<string, string>();
                    properties.Add("StepText", JsonConvert.SerializeObject(bookingDetails)); 
                    this.TelemetryClient.TrackEvent("CustomEvents", properties);

```
