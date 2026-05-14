# Getting Started with Service A

## Installation

```bash
npm install service-a
```

## Configuration

Add the following to your config file:

```yaml
service:
  name: service-a
  port: 3000
```

## Usage

```javascript
const serviceA = require('service-a');
serviceA.start();
```
