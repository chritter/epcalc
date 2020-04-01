
## Svelte

* Svelte automatically updates the DOM when your component's state changes. Often, some parts of a component's state need to be computed from other parts (such as a fullname derived from a firstname and a lastname), and recomputed whenever they change.
* reactive declarations: $: doubled = count * 2; all will be recomputed;
* powerful system of reactivity for keeping the DOM in sync with your application state
    * <button on:click={handleClick}> executes function


