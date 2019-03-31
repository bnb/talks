# Automating Your Vulnerabilities Away

Title:
```
Automating Your Vulnerabilities Away
```

Abstract:
```
Your apps are insecure. Not because of third-party dependenceis, but because of the runtime itself.

Node.js actively ships security updates, patching publicly disclosed vulnerabilities... and you're not shipping them into production.

This talk will go over how you can manage Node.js versions for production to ensure that you're always safe.
```

Full:
```
Your production Node.js applications are insecure. These vulnerabilities aren't coming from the module ecosystem, as you may expect – they're coming from your own engineering practices. Node.js versions are the root cause of vulnerabilities in production that your team isn't managing effectively. But, there's a light at the end of the tunnel – that light is automation.

The Node.js project actively ships updates often and with notice, and does their best to effectively communicate the changes that specifically revolve around security releases. Nevertheless, your Node.js versions are a few releases behind because your app _works_ regardless of the Node.js version that's running – as such, upgrading is a lower priority than literally anything else you could possibly be doing.

In this talk you'll learn about the resources that are currently available to help you and your ops team keep your Node.js versions up to date, covering your apps from being attacked with publicly disclosed vulnerabilities.
```
