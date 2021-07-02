# vue-simple-agenda
Simple Agenda component for Vue, where you can add important events to a simple calendar.

## Steps:
```sh
npm i vue-simple-agenda
```
Then in your component where you wish to use vue-simple-agenda:
```sh
import VueAgenda from 'vue-simple-agenda'
```
And finally inside your Vue template code:
```sh
<template>
  <div id="app">
    <vue-agenda />
  </div>
</template>
```

## Props
| Name | Description | Default |
| ------ | ------ | ------ |
| beginning | Start of the worktime for the agenda | {hour: 8, minute: 25} |
| end | Start of the worktime for the agenda | {hour: 16,minute: 30} |
| date | Day from which agenda starts. It spans for 7 days. | ```new Date()``` / current date |
| items | List of agenda items, or meetings | ```[ {title: "Meeting 1", start: { hour: 13, minute: 45 },
end: { hour: 14, minute: 55 }, day: 1 } ]``` |


