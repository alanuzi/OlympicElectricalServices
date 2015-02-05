---
layout: default
title: Enquiry
permalink: /enquiry/
---

<form role="form" action="mailto:alanuzi@googlemail.com" method="post" enctype="text/plain">
  <div class="form-group">
  	<label for="name">Name:</label>
    <input type="text" class="form-control" id="name">
    <label for="phone">Phone:</label>
    <input type="text" class="form-control" id="phone">
    <label for="email">Email address:</label>
    <input type="email" class="form-control" id="email">
    <div class="checkbox">
      <label><input type="checkbox" value="">Domestic</label>
    </div>
    <div class="checkbox">
      <label><input type="checkbox" value="">Commercial</label>
    </div>
    <label for="comment">Enquiry:</label>
  	<textarea class="form-control" rows="5" id="comment"></textarea>
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>