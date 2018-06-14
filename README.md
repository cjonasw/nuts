# nuts
Simple typescript package

`npm run build`

then include in your projects:

```
import { Component } from '@angular/core';
import { Nut } from 'nuts';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  title = 'app';

  constructor(){
    console.log(new Nut());
  }
}
```

Package building is particularly important for Angular (6.0.3) as it doesn't currently support compiling files outside of `src/`
