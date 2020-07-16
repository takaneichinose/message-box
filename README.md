# Responsive Message Box
<p>This Message Box implementation in Javascript, inspired by material design's toast message.</p>
<p>Note: I used the VanillaJS (native Javascript) Class to implement the message box. This may not work on older browsers, due to compatibility issue with native class.</p>
<p>This is resolvable by using Javascript compilers or pre-processesors, to compile the Javascript code into cross-browser Javascript code.</p>
<hr />
<h3>Usage</h3>
<ol>
  <li>
    <h4>Create MessageBox class instance</h4>
    <code>
      let msg = new MessageBox("#id", option)
    </code>
  </li>
  <li>
    <h4>Available options (type: Object)</h4>
    <ol type="a">
      <li>
        <h6>closeTime</h6>
        <p>Time before the message box closes (In milliseconds). 0 to make it persistent</p>
      </li>
      <li>
        <h6>hideCloseButton</h6>
        <p>To hide the close button</p>
      </li>
    </ol>
  </li>
  <li>
    <h4>Call the "show" method to show the dialog box</h4>
    <h5>Parameters</h5>
    <ul>
      <li>
        <h6>message</h6>
        <p>The message that will appear on the message box</p>
      </li>
      <li>
        <h6>label</h6>
        <p>The label of the close button (default is "CLOSE")</p>
      </li>
      <li>
        <h6>callback</h6>
        <p>Callback function</p>
      </li>
    </ul>
  </li>
</ol>
