What is Logging?
In programming, logging refers to the process of recording or storing information or messages that help in understanding the behavior and execution of a program.
It’s like keeping a logbook for your software, where you record events, errors, and other important details. Just as a ship’s captain uses a logbook to track their journey, 
developers use logs to keep track of what their code is doing1. Proper logging is crucial for debugging, maintaining code, and ensuring robust applications.

There are two main types of logging:

Diagnostic Logging: This records events during runtime, such as method calls, input/output, HTTP requests, and SQL executions. 
It helps developers understand how the code executes and identify issues.
Audit Logging: Responsible for recording abstract business logic events, like user actions (adding/editing/removing content) or other events with managerial or legal value. 
Audit logs provide insights beyond technical details.

Why Logging is important

Logging is crucial for several reasons:
Debugging: When things go wrong, logs provide a trail of events, helping developers identify issues and fix them efficiently.
Monitoring: Logs allow real-time monitoring of application behavior. DevOps teams can detect anomalies and respond promptly.
Security: Audit logs track user actions, aiding in security investigations and compliance.
Performance: Analyzing logs helps optimize code and improve performance.
Historical Context: Logs serve as a historical record, valuable for troubleshooting and understanding system behavior.

What are Logging Levels?
Logging Levels are:

DEBUG: Detailed information for debugging purposes. Use this during development to trace code execution.
INFO: General information about the application’s operation. Useful for tracking important events.
WARNING: Indicates potential issues that don’t prevent the application from running but might need attention.
ERROR: Indicates errors that caused a specific operation to fail. These should be investigated.
CRITICAL: A severe error that might lead to application failure. Immediate attention required.
