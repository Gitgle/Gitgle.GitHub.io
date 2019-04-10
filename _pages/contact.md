---
title: "留言"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">请将您的留言信息发送至我们，我们会尽快回复！</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="姓名*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail 地址*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="留言信息*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>
