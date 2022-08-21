## Note
nid: 1602349882061
model: Basic-b122e
tags: Eigene
markdown: false

### Front
Was unterscheidet schwergewichtige Prozesse von Threads?

### Back
<ul>
  <li>A <strong>normal process</strong> under an Operating System
  (OS) is a heavy-weight process. For each such process, the OS
  provides an <strong>independent address space</strong>, this way
  keeping different users and services separated. Switching from
  one such process to another is time consuming, though modern
  machines contain a special unit, the Memory Management Unit
  (MMU), dedicated to the task.
  <li>A <strong>Light-Weight Process (LWP)</strong>, also called
  thread, runs under the address space of a normal (heavy-weight)
  process, and LWPs under the same process <strong>may share e.g.
  variables</strong>. Switching from one LWP to another is much
  <strong>faster</strong> than switching from one heavy-weight
  process to another, because there is less to manage, and the MMU
  is not involved.
</ul>
