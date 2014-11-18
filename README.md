IfByPhone-SMS-Robot
===================

This PHP class is designed as a server-side complement to your IfByPhone.com Account, to be used as an SMS handler end-point (or can be adapted to handle inbound HTTP requests for nearly any SMS API). It has it's own internal installation, configuration &amp; troubleshooting methods, and is able to receive inbound SMS messages, stores them in MySQL &amp; flat text file, response to them with pre-specified messages, parses and intelligently responds to control commands ("HELP", "STOP", "UNSUBSCRIBE", etc), tracks and enforces opt-in and opt-out preferences. Advanced features include user identification through token pairs, parsing of offer codes, etc.
