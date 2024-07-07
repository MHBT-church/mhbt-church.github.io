---
title: "Our Leaders"
draft: false
---
# This is a page about leaders

![This is an image](/img/freely-26905.jpg)

<!--
{{ $map := dict "a" "foo" "b" "bar" "c" "baz" }}
{{ index $map "c" }} → baz
-->
{{ $map := dict "leaderName" "A. Jones" "leaderTitle" "Pastor" }}

<div>
  <h3> {{ index $map "leaderName" }} </h3>
  <h4> {{ index $map "leaderTitle" }} </h4>
  <p> {{ .Title }}</p>
</div>

<!-- iterate through a list of leaders with a picture and description with Hugo templating -->