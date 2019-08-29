- Create a new app: ng new name-of-app (select yes for routing.)
    - Anuglar routing allows you to create routes between your components in your application.

- ng serve -o (simimar to npm start for create-react-app.)
    - reloads automatically

- e2e (end to end testing)

- node modules: for our dependencies

- app: where we will spend the most time writting code.
    - app.component.ts has three main sections
        1. import { Component } from '@angular/core';   // our imports
        2. Component Decorator: includes main app-root,location to templete file, the styles for css 
        3. The component locgic: export class AppComponent

// Create a navbar
<header>
  <div class="container">
    <a href="#" class = "logo">Getting the basics</a>
    <nav>
      <ul>
        <li><a href = "#"  routerLink = "/">Home</a></li> <!--routerLink is how you link to the different pages-->
        <li><a href = "#" routerLink = "/list">NicKnacks</a></li>
      </ul>
    </nav>
  </div>
</header>

https://www.youtube.com/watch?v=_TLhUCjY9iA
11 min mark

