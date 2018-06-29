
# Secure, Client-Side, Network-Free JSON Linting

by [Ben Nadel][bennadel]

This app provides a super simple user interface (UI) that attempts to parse a given input
as a JSON string. If the input can be parsed successfully, it is pretty-printed to the
output. If the input cannot be parsed, the error message is displayed to the user.

The goal of this app is to provide basic JSON linting functionality with **zero dependencies**
and **zero network traffic**. This way, you - as the consumer - can rest assured that **no one
else can see the data** that you paste into the input. Since no data is submitted over the
network, no data ever leaves your computer. And, since no ads are rendered on the page,
there's no chance of any 3rd-party sites getting compromised and injecting malicious code
alongside your sensitive data.


bennadel: https://www.bennadel.com
