# Hydrogen Calendar Embeds - CSS Classes Reference

CSS classes available for styling your calendars.


## Hydrogen Calendar Embeds Classes

| Class | Description |
|-------|-------------|
| `.hycal-container` | Main calendar wrapper |
| `.hydrogen-calendar-embeds` | Alternative wrapper class |
| `#hycal-{instance_id}` | Unique ID for each calendar instance |
| `.hycal-event-{id}` | Event styling by calendar index or custom `cal_ids` |
| `.hycal-calendar-{id}-event` | Alternative event class |
| `.hycal-ics-event` | All events from ICS feeds |
| `.hycal-branding` | "Powered by" branding text |
| `.hycal-error` | Error message display |

### Tooltip Classes

| Class | Description |
|-------|-------------|
| `.hycal-calendar-{id}-popup` | Tooltip popup by calendar |
| `.hycal-event-title` | Event title in tooltip |
| `.hycal-event-time` | Time container |
| `.hycal-event-start-time` | Start time |
| `.hycal-event-end-time` | End time |
| `.hycal-event-location` | Location container |
| `.hycal-event-location-link` | Location Google Maps link |
| `.hycal-location-icon` | Map pin icon |
| `.hycal-event-description` | Description text |
| `.hycal-event-actions` | Action buttons container |
| `.hycal-map-button` | Map button |
| `.hycal-add-to-google-button` | Add to Google button |
| `.hycal-open-event-button` | Open Event button |
| `.hycal-download-ics-button` | Download ICS button |
| `.hycal-tooltip-close` | Close button |
| `.tippy-content` | Tippy.js tooltip content wrapper |
| `.tippy-box[data-theme~="light"]` | Light theme tooltip box |


## FullCalendar Classes

Hydrogen Calendar Embeds uses [FullCalendar](https://fullcalendar.io/) for rendering. See - [FullCalendar CSS Documentation](https://fullcalendar.io/docs/css-customization) for full details.

### Toolbar

| Class | Description |
|-------|-------------|
| `.fc-toolbar` | Toolbar container |
| `.fc-header-toolbar` | Main header toolbar |
| `.fc-toolbar-title` | Calendar title (month/year) |
| `.fc-button` | Toolbar buttons |
| `.fc-button-active` | Active view button |

### Day Grid

| Class | Description |
|-------|-------------|
| `.fc-daygrid` | Day grid container |
| `.fc-daygrid-day` | Individual day cell |
| `.fc-daygrid-day-number` | Day number |
| `.fc-day-today` | Today's date |
| `.fc-day-past` | Past dates |
| `.fc-day-future` | Future dates |
| `.fc-col-header-cell-cushion` | Day of week header |

### Events

| Class | Description |
|-------|-------------|
| `.fc-event` | Any calendar event |
| `.fc-event-past` | Past events (50% opacity by default) |
| `.fc-event-title` | Event title in calendar |
| `.fc-h-event` | Horizontal event (spanning days) |
| `.fc-event-main-frame` | Event content frame |

### List View

| Class | Description |
|-------|-------------|
| `.fc-list` | List view container |
| `.fc-list-day` | Day header in list |
| `.fc-list-event` | Event in list view |
