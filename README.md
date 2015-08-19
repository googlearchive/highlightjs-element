highlightjs-element
===================

Element wrapper for the `highlightjs` (http://highlightjs.org/) library.

##### Example

    <highlightjs-element text="def somefunc(param1='', param2=0):"></highlightjs-element>

##### Example

    <highlightjs-element>
      <template>

        <link rel="import" href="/components/polymer/polymer.html">
        <dom-module name="my-element">
          <template>
            <span>I'm <b>my-element</b>. Check out my prototype.</span>
          </template>
          <script>
            Polymer({is: 'my-element'});
          </script>
        </dom-module>

      </template>
    </highlightjs-element>
