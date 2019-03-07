# calendar-federation

This manages the federated calendar and event configuration for the [network of fab labs in Brandenburg](http://brandenburger-maker.github.io/).

**[Kalender anzeigen/View Calendar][web-link]**

## Sources
[sources]: #sources

The calendar includes the sources from 

- [TH Wildau](https://vinnlab.th-wildau.de/events)
- [Mia](http://www.maedchentreff-cottbus.de/werkstatt/)
- [FabLab Cottbus](http://blog.fablab-cottbus.de/veranstaltungskalender/)
- [Offene Werkstatt Spremberg](https://www.owspremberg.de/terminliste/)

### Add Sources

If you add a source, add it
- in the [sources] section
- in the [configuration]

## Implementation and Sharing

The base is the [open-web-calendar].
You can find the configuration in the [calendar-configuration.json][configuration] file.

You can share the calendar as embeddable code:
```html
<iframe id="open-web-calendar" 
    src="https://open-web-calendar.herokuapp.com/calendar.html?specification_url=https%3A%2F%2Fraw.githubusercontent.com%2FBrandenburger-Maker%2Fcalendar-federation%2Fmaster%2Fcalendar-configuration.json" 
    allowTransparency="true" scrolling="no" 
    frameborder="0" height="600px" width="100%"></iframe>
```
You can subscribe to it soon via the [ICS link].
You can share a [link to the web calendar][web-link].

[open-web-calendar]: https://github.com/niccokunzmann/open-web-calendar
[configuration]: calendar-configuration.json
[ICS Link]: https://open-web-calendar.herokuapp.com/calendar.ics?specification_url=https%3A%2F%2Fraw.githubusercontent.com%2FBrandenburger-Maker%2Fcalendar-federation%2Fmaster%2Fcalendar-configuration.json
[web-link]: https://open-web-calendar.herokuapp.com/calendar.html?specification_url=https%3A%2F%2Fraw.githubusercontent.com%2FBrandenburger-Maker%2Fcalendar-federation%2Fmaster%2Fcalendar-configuration.json
