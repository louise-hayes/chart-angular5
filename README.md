# chart-angular5

Test version - working version coming soon.

# To install as npm package
npm install chart-angular5

edit app.module.ts
import { ChartModule } from 'chart-angular5';
@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    ChartModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }

Add <app-chart></app-chart> to app.component.html

# To install as git plugin 
add the below line to package.json


# Git:
https://github.com/louise-hayes/chart-angular5.git


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

