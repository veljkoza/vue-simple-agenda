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
| end | Start of the worktime for the agenda | {hour: 8, minute: 25} |
| date | Day from which agenda starts. It spans for 7 days. | new Date() / current date |

