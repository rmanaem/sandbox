<template>
  <div id="app">
    <query-form></query-form>
  </div>
</template>

<script>
import QueryForm from "./components/QueryForm.vue";
export default {
  name: "App",
  components: { "query-form": QueryForm },
};
</script>

<style>
/*

Author: Jonathan Armoza

/* Tags */

/* Classes */

/* Card */

.btn-group {
  padding-right: 0.5em;
}
.btn-toolbar {
  padding-right: 0;
}
.card {
  background-color: rgb(242, 242, 242);
  border-radius: 10px;
  color: black;
}
.card-checkbox {
  padding-right: 0;
}
.card-content {
  padding-left: 0;
}
.card-dataset-source {
  color: red;
  font-size: 1em;
}
.card-modality {
  font-size: 1em;
}
.card-text {
  font-size: 1.25em;
}
.card-title {
  font-size: 1.75em;

  /* Ellipsis length truncation */
  max-width: 100%;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/* IDs */

/* Card list */
#card-listbox {
  border: 1em;
  border-color: gray;
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  height: 65vh;
  overflow-y: auto;
}

#download-results-button {
  background-color: #0d6efd;
  color: white;
  /* visibility: hidden; */
}

#download-results-link {
  color: white;
  text-decoration: none;
}

#query-controls {
  padding-top: 1em;
  padding-bottom: 1em;
}

/* #query-fields-column {

    margin-right: 1em;
}

#query-results-column {

    margin-left: 1em;
} */

#repo-row {
  padding-bottom: 1em;
}

#results-list-group {
  padding-right: 0;
}

#summary-stats {
  float: right;
}
</style>
