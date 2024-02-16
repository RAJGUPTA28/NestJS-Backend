# NEST JS
A progressive Node.js framework for building efficient, reliable and scalable server-side applications.

**Setup**
---
```
$ npm i -g @nestjs/cli
$ nest new project-name
```

**Controllers**
--- 
  Controllers are responsible for handling incoming requests and returning responses to the client.
``` @Controller() decorator```

To create a controller using the CLI, simply execute the ``` $ nest g controller [name] ``` command.

**Providers**
---
A provider is an object that provides an instance of a service to other application components
Providers are created through classes that have the ```@Injectable()``` decorator and are registered in modules through the ```providers``` method.
