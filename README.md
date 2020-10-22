# MVC
<pre>
.model
load .data
write .data

.view
open .controller
print foo

.controller
open .model
foo = read .model
if $1
bar = update model $1
<pre>
