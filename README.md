# Weather

## Fix for App Transport Security Override

```XML
<key>NSAppTransportSecurity</key>
  <dict>
    <key>NSExceptionDomains</key>
  <dict>
    <key>openweathermap.org</key>
    <dict>
      <key>NSIncludesSubdomains</key>
      <true/>
      <key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
      <true/>
    </dict>
  </dict>
</dict>
```
