A label is a key-value pair, stored as a string.

A LABEL is a piece of metadata on an image. You can add any key=val as a LABEL. An ARG is something you can pass at build time, to the builder.

Why use Docker labels?
Image result for what is a label in dockerfile
Docker image labels are a way for you to add key-value metadata to your image itself.

 You can specify multiple labels for an object, but each key must be unique within an object. If the same key is given multiple values, the most-recently-written value overwrites all previous values