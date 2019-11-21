<template>
    <b-navbar spaced type="is-primary">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item href="#" class="is-italic">
                HOME
            </b-navbar-item>
            <b-navbar-item href="#" class="is-italic">
                CONTACT US
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <b-field>
                    <b-input placeholder="Phone number"></b-input>
                    <b-input style="margin-left: 2rem;" placeholder="Password"></b-input>
                </b-field>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>
