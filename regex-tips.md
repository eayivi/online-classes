<H3>Tips</H3>
    <div>
      <div style="width:43%;float:left">
        <table border="1">
          <tr valign="top">
            <th>
              Expression</th><th>Matches</th></tr>
          <tr valign="top">
            <td>[abc]</td>
            <td>A single character: a, b, or c</td>
          </tr>
          <tr valign="top">
            <td>[^abc]</td>
            <td>Any single character <em>but</em> a, b, or c</td>
          </tr>
          <tr valign="top">
            <td>[a-z]</td>
            <td>Any character in the range a-z</td>
          </tr>
          <tr valign="top">
            <td>[a-zA-Z]</td>
            <td>Any character in the range a-z or A-Z (any alphabetical character)</td>
          </tr>
          <tr valign="top">
            <td>\s</td>
            <td>Any whitespace character [ \t\n\r\f\v]</td>
          </tr>
          <tr valign="top">
            <td>\S</td>
            <td>Any non-whitespace character [^ \t\n\r\f\v]</td>
          </tr>
          <tr valign="top">
            <td>\d</td>
            <td>Any digit [0-9]</td>
          </tr>
          <tr valign="top">
            <td>\D</td>
            <td>Any non-digit [^0-9]</td>
          </tr>
          <tr valign="top">
            <td>\w</td>
            <td>Any word character [a-zA-Z0-9_]</td>
          </tr>
          <tr valign="top">
            <td>\W</td>
            <td>Any non-word character [^a-zA-Z0-9_]</td>
          </tr>
          <tr valign="top">
            <td>\b</td>
            <td>A word boundary between \w and \W</td>
          </tr>
          <tr valign="top">
            <td>\B</td>
            <td>A position that is not a word boundary</td>
          </tr>
          <tr valign="top">
            <td>|</td>
            <td>Alternation: matches either the subexpression to the left or to the right</td>
          </tr>
          <tr valign="top">
            <td>()</td>
            <td>Grouping: group all together for repetition operators</td>
          </tr>
          <tr valign="top">
            <td>^</td>
            <td>Beginning of the string</td>
          </tr>
          <tr valign="top">
            <td>$</td>
            <td>End of the string</td>
          </tr>
        </table>
      </div>
      <div style="width:5%;float:left">&#160;</div>
      <div style="width:43%;float:left">
        <table border="1">
          <tr valign="top">
            <th>
              Repetition&#160;Operator</th><th>Meaning</th></tr>
          <tr valign="top">
            <td>{n,m}</td>
            <td>Match the previous item at least <em>n</em> times but no more than <em>m</em>
              times</td>
          </tr>
          <tr valign="top">
            <td>{n,}</td>
            <td>Match the previous item <em>n</em> or more times</td>
          </tr>
          <tr valign="top">
            <td>{n}</td>
            <td>Match exactly <em>n</em> occurrences of the previous item</td>
          </tr>
          <tr valign="top">
            <td>?</td>
            <td>Match 0 or 1 occurrences of the previous item {0,1}</td>
          </tr>
          <tr valign="top">
            <td>+</td>
            <td>Match 1 or more occurrences of the previous item {1,}</td>
          </tr>
          <tr valign="top">
            <td>*</td>
            <td>Match 0 or more occurrences of the previous item {0,}</td>
          </tr>
        </table><br />
        <table border="1">
          <tr>
            <th>Option</th><th>Description</th>
          </tr>
          <tr>
            <td>g</td>
            <td>"<u>G</u>lobal" -- find all matches in the string rather than
              just the first</td>
          </tr>
          <tr>
            <td>i</td>
            <td>"case <u>I</u>nsensitive" -- ignore character case when matching</td>
          </tr>
          <tr>
            <td>m</td>
            <td>"<u>M</u>ultiline" -- search over more than one line if the
              text contains line breaks</td>
          </tr>
        </table>
      </div>
    </div>
