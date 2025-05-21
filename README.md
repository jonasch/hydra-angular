# HydraAngular



## 🪛 Aufgabe
Baue eine Angular Anwendung nach folgenden Anforderungen von unserem fiktiven Product Owner.\
🧘‍♂️ Kein Stress, es muss nicht alles geschafft und auch nicht perfekt werden.\
🤙APIs werden verlinkt und API Keys zur Verfügung gestellt.\
😉 Die Aufgaben sind inkrementell aufgebaut

1. Der Product Owner möchte eine Seite mit Bildern. Binde einen Service an, der Bilder von einer bereitgestellten REST Schnittstelle holt. Stelle diese Bilder dar.
   - Bilder Service: https://unsplash.com/documentation
   - api-key (client_id) = ```[PHOTO_CLIENT_ID]```
   - ```GET 'https://api.unsplash.com/photos?per_page=5&client_id=[PHOTO_CLIENT_ID]'```


2. Der Product Owner möchte die angezeigten Bilder kontrollieren. Füge ein Suchfeld hinzu. Wenn man einen Begriff eingibt, werden Bilder für diesen Begriff gesucht. 
Unser PO hat gesagt, dass das Augenmerk hierbei auf Städtenamen liegen soll.
    - GET '/search/photos?query=...&client_id=[PHOTO_CLIENT_ID]'


3. Unser PO findet das Wetter voll wichtig. Deswegen möchte er nun, dass aktuelle Wetterdaten für die gesuchte Stadt angezeigt werden. Neben dem Bild.
   - Wetter service: https://openweathermap.org/
   - geocoding: https://openweathermap.org/api/geocoding-api 
   - current weather: https://openweathermap.org/current#geo
   - api-key (appid): ```[WEATHER_APP_ID]```
   - e.g. ```GET 'http://api.openweathermap.org/data/2.5/weather?...&appid=[WEATHER_APP_ID]'```


4. Zu guter Letzt möchte unser PO nicht nur das aktuelle Wetter, sondern auch einen Forecast über die nächsten 5 Tage
    - forecast: https://openweathermap.org/forecast5


5. Unser PO hat so gut verdient, dass er jetzt mehrere Wohnsitze hat. Folgerichtig, möchte er mehrere Städte angezeigt bekommen. 
D.h. mit jeder Suche eine Stadt in die Liste hinzufügen, aber auch entfernen können.






# Angular Readme starts here

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.11.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
