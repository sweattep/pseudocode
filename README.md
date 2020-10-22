# MVC
<pre>
.model
open .data
foo = read .data
if update
  write .data

.view
open .controller
print foo

.controller
open .model
bar = read .model
if $1
  baz = update model $1
<pre>
