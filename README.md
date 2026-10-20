<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&pause=1000&color=3FB950&vCenter=true&repeat=false&width=310&height=24&lines=~%2Fascended-parth+%24+whoami+--show"
    alt="~/ascended-parth $ whoami --show"
  />
</p>

<h1 align="center">𝑝𝑎𝑟𝑡ℎ ☆</h1>

<p align="center">
  <samp>cs student · machine learning · python enthusiast · night rider · learning rust</samp>
</p>

<p align="center">
  <b>i build models that think in loops.</b><br />
  <sub>running everything locally · chasing a frontier model &amp; a 765 rs</sub>
</p>

<br />

<h3>𝑠𝑡𝑎𝑡𝑢𝑠</h3>

<pre>
<b>currently</b>   :: building a recursive language model (rlm)
<b>focus</b>       :: python, machine learning &amp; picking up rust
<b>off-screen</b>  :: motorcycle rides &amp; cooking
<b>endgame</b>     :: local frontier model + triumph street triple 765 rs
</pre>

<br />

<h3>𝑏𝑢𝑖𝑙𝑑𝑖𝑛𝑔</h3>

<p align="center">
  <img
    src="https://img.shields.io/badge/rlm-%20in%20progress-000000?style=for-the-badge&logo=github&logoColor=3FB950"
    height="24"
    alt="rlm — in progress"
  />
</p>

**Recursive Language Model** — a language model that gets to call itself.

A normal LLM gets one shot at a fixed context window. An RLM treats its own
generation as a subroutine: it splits a prompt into sub-tasks, spawns recursive
calls that reason over each piece in isolation, then folds every partial answer
back into one final response. Context stops being a wall — it becomes a stack.

<pre>
        ┌── root call ─────────────────────────────────────────┐
        │  decompose                                           │
        │     ├──► child(task_a) ──► answer_a                  │
        │     ├──► child(task_b) ──► answer_b                  │
        │     └──► child(task_c) ──► answer_c                  │
        │                    │                                  │
        │                    ▼                                  │
        │             fold(answers) ──► final answer            │
        └───────────────────────────────────────────────────────┘
</pre>

<pre>
<b>status</b>   :: building
<b>stack</b>    :: python · pytorch · custom inference loop
<b>goal</b>     :: run it locally on a single gpu
</pre>

<br />

<h3>𝑠𝑡𝑎𝑐𝑘 &amp; 𝑡𝑜𝑜𝑙𝑠</h3>

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=python,rust,js,ts,linux,arch,git,nix,vscode,neovim,pytorch,cmake,bash,docker"
    alt="python, rust, typescript, javascript, linux, arch, nix, pytorch, cmake, docker"
