### What is AMQP?

AMQP stands for **Advanced Message Queuing Protocol**. It is an open standard protocol used for passing messages between systems in a message-oriented middleware architecture. AMQP enables reliable communication using message queues and supports features like message delivery guarantees, routing, and publish-subscribe patterns. It is commonly used with message brokers such as RabbitMQ.

---

### What does `guest:guest@localhost:5672` mean?

This is a connection string for connecting to an AMQP broker (like RabbitMQ):

- The first `guest` is the **username** used to authenticate with the broker.
- The second `guest` is the **password** for that user.
- `localhost:5672` is the address of the broker:
    - `localhost` indicates the broker is running on the local machine.
    - `5672` is the default **port number** used by AMQP for connections.

In summary, `guest:guest@localhost:5672` tells the system to connect to a RabbitMQ server running locally, using the default credentials (`guest`/`guest`) on port 5672.