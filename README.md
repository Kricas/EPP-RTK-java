# EPP-RTK-java
Hello my name is José

I am trying to connect to the server from my registrar and it always gives me the same error I already tried with multiple certificates and I can not connect.

The error is as follows

Start of the Session example
Connecting to the EPP Server and getting the greeting
Exception! [com.tucows.oxrs.epprtk.rtk.transport.EPPTransportException] [Failed to establish secure connection to server. Perhaps a bad certificate? -- use -Djavax.net.debug=all to see errors.]
com.tucows.oxrs.epprtk.rtk.transport.EPPTransportException: Failed to establish secure connection to server. Perhaps a bad certificate? -- use -Djavax.net.debug=all to see errors.
at com.tucows.oxrs.epprtk.rtk.transport.EPPTransportTCPTLS.connect(EPPTransportTCPTLS.java:183)
at com.tucows.oxrs.epprtk.rtk.EPPClient.connect(EPPClient.java:452)
at com.tucows.oxrs.epprtk.rtk.EPPClient.connectAndGetGreeting(EPPClient.java:657)
at com.tucows.oxrs.epprtk.rtk.example.SessionExample.main(SessionExample.java:129)

Someone can help me?

best reguarde José Gonçalves
