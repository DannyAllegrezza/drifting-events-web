<template>
<div id="app">
    <section class="container">
      <div class="has-text-centered">
        <!-- <img src="./assets/logo.png"> -->

      </div>
      <hr>

      <h1 class="title">Buefy Customization Basic Setup</h1>
      <b-field>
        <b-checkbox>Checkbox</b-checkbox>
      </b-field>

      <b-field>
        <b-switch>Default</b-switch>
      </b-field>

      <b-field label="Name">
        <b-input placeholder="John Silver"></b-input>
      </b-field>

      <div class="block">
        <b-icon icon="person"></b-icon>
        <b-icon icon="home"></b-icon>
        <b-icon icon="dashboard"></b-icon>
      </div>

      <b-message title="Danger with icon" type="is-danger" has-icon>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id fermentum quam. Proin sagittis, nibh id hendrerit imperdiet, elit sapien laoreet elit
      </b-message>

      <b-field>
        <b-dropdown>
          <button class="button" slot="trigger">
            <span>Filters</span>
            <b-icon icon="arrow_drop_down"></b-icon>
          </button>

          <b-option value="open_issues">Open Issues and Pull Requests</b-option>
          <b-option value="your_issues">Your Issues</b-option>
          <b-option value="pull_requests">Your Pull Requests</b-option>
          <b-option value="everything">Everything</b-option>
        </b-dropdown>

        <b-input icon="search" type="search" placeholder="Search..."></b-input>
      </b-field>

    </section>
  </div>
</template>

<script>
export default {}
</script>
