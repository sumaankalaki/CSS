ATTRIBUTE SELECTOR:
The CSS attribute selector matches elements based on the presence or value of a given attribute.

      /* <a> elements with a title attribute */
      a[title] {
        color: purple;
      }
      <a href="#" title="Link with title">Link 1</a>

      
      /* <a> elements with an href matching "https://example.org" */
      a[href="https://example.org"] {
        color: green;
      }
      <a href="https://example.org">Link to Example.org</a>

      
      /* <a> elements with an href containing "example" */
      a[href*="example"] {
        font-size: 2em;
      }
      <a href="https://www.example.com">Example Link</a>

      
      /* <a> elements with an href starting with "https" */
      a[href^="https"] {
        font-size: 2em;
      }
      <a href="https://www.example.com">HTTPS Link</a>

      
      /* <a> elements with an href ending ".org" */
      a[href$=".org"] {
        font-style: italic;
      }
      <a href="https://www.example.org">Org Link</a>

      
      /* <a> elements whose class attribute contains the word "logo" */
      a[class~="logo"] {
        padding: 2px;
      }
      <a href="#" class="company-logo">Company Logo Link</a>
