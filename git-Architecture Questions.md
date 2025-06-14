// Node.js handles multiple concurrent connection using Event-driven architecture, non-blocking it doesn’t wait for I/O operations to complete, instead it continues processing other requests and it will call it back to handle it when it ready.

// Non-blocking means that Node.js don’t wait for I/O operations to complete, instead it continues executing other task and handles I/O operations response when it’s ready.

// Node.js listens for specific events, e.g. completed or incoming task and it triggers callback function to handle events. This make Node.js very efficient in handling multiple tasks at a time and also give room to other processing task in the background
