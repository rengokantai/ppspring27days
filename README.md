# ppspring27days

```
@Controller
@RequestMapping
@GetMapping
@PostMapping
@RequestParam
```



## Testing Your App
```
mockmvc = MockMVCBuilders.webAppContextSetup(context).alwaysDo(print()).build()
```

## Creating Your First REST
### REST vs SOAP
Rest
- representational state transfer
- Defines a set of constraints to be used to create web services
- REST is an architectual style

Soap
- expose their own sets of operations
- soap is a protocol

Formal rest constraints
- Client-server architecture
- Statelessness

Uniform interface
- Resource identification in request
- Resource manipulation through repression
```
```


Uniform interface
- Resource identified in request
- Resource manipulation through representation

Restful | MVC
--- | ---
@RestfulController marks the class as a controller where every method returns a domain object instead of a view | Method in @Controller classes return a view source
--- | ---
A restful web service populates and returns an object, which is directly written to Http-Response as JSON | MVC relies on a view resolver to perform server-side rendering of objects
