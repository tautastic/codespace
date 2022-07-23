---
draft: true
date: 2022-07-23
author: "Ahmed Sami"
title: "Symbole in der Mathematik"
categories: [ "Mathematik" ]
summary: "Eine Übersicht des Griechischen Alphabets und der Aussagen- und Mengensymbole."
math: true
---

{{< css.inline >}}

<style>
@media screen and (min-width:800px) {
    .post-content table th {font-size: 1.2rem;min-width: 113px;}
}
@media screen and (min-width:600px) {
    .table-desktop {display: block;}
    .table-mobile {display: none;}
}
@media screen and (max-width:600px) {
    .table-mobile table th {font-size: 1.2rem;min-width: 113px;}
    .table-desktop {display: none;}
    .table-mobile {display: block;}
}
</style>

{{< /css.inline >}}

## Griechisches Alphabet

<table class="table-desktop">
<tbody>
<tr><td style="border: 0; border-right: 4px solid var(--border);">

|    Groß     |           Klein           |  Name   |
|:-----------:|:-------------------------:|:-------:|
|  $\\Alpha$  |         $\\alpha$         |  Alpha  |
|  $\\Beta$   |         $\\beta$          |  Beta   |
|  $\\Gamma$  |         $\\gamma$         |  Gamma  |
|  $\\Delta$  |         $\\delta$         |  Delta  |
| $\\Epsilon$ | $\\epsilon, \\varepsilon$ | Epsilon |
|  $\\Zeta$   |         $\\zeta$          |  Zeta   |
|   $\\Eta$   |          $\\eta$          |   Eta   |
|  $\\Theta$  |   $\\theta, \\vartheta$   |  Theta  |
|  $\\Iota$   |         $\\iota$          |  Iota   |
|  $\\Kappa$  |   $\\kappa, \\varkappa$   |  Kappa  |
| $\\Lambda$  |        $\\lambda$         | Lambda  |
|   $\\Mu$    |          $\\mu$           |   Mu    |

</td><td style="border: 0">

|    Groß     |       Klein       |  Name   |
|:-----------:|:-----------------:|:-------:|
|   $\\Nu$    |      $\\nu$       |   Nu    |
|   $\\Xi$    |      $\\xi$       |   Xi    |
|     $O$     |        $o$        | Omikron |
|   $\\Pi$    |      $\\pi$       |   Pi    |
|   $\\Rho$   | $\\rho, \\varrho$ |   Rho   |
|  $\\Sigma$  |     $\\sigma$     |  Sigma  |
|   $\\Tau$   |      $\\tau$      |   Tau   |
| $\\Upsilon$ |    $\\upsilon$    | Upsilon |
|   $\\Phi$   | $\\phi, \\varphi$ |   Phi   |
|   $\\Chi$   |      $\\chi$      |   Chi   |
|   $\\Psi$   |      $\\psi$      |   Psi   |
|  $\\Omega$  |     $\\omega$     |  Omega  |
</td></tr></tbody> </table>

<table class="table-mobile">
<tbody>
<td style="border: 0">

|    Groß     |           Klein           |  Name   |
|:-----------:|:-------------------------:|:-------:|
|  $\\Alpha$  |         $\\alpha$         |  Alpha  |
|  $\\Beta$   |         $\\beta$          |  Beta   |
|  $\\Gamma$  |         $\\gamma$         |  Gamma  |
|  $\\Delta$  |         $\\delta$         |  Delta  |
| $\\Epsilon$ | $\\epsilon, \\varepsilon$ | Epsilon |
|  $\\Zeta$   |         $\\zeta$          |  Zeta   |
|   $\\Eta$   |          $\\eta$          |   Eta   |
|  $\\Theta$  |   $\\theta, \\vartheta$   |  Theta  |
|  $\\Iota$   |         $\\iota$          |  Iota   |
|  $\\Kappa$  |   $\\kappa, \\varkappa$   |  Kappa  |
| $\\Lambda$  |        $\\lambda$         | Lambda  |
|   $\\Mu$    |          $\\mu$           |   Mu    |
|   $\\Nu$    |          $\\nu$           |   Nu    |
|   $\\Xi$    |          $\\xi$           |   Xi    |
|     $O$     |            $o$            | Omikron |
|   $\\Pi$    |          $\\pi$           |   Pi    |
|   $\\Rho$   |          $\\rho$          |   Rho   |
|  $\\Sigma$  |         $\\sigma$         |  Sigma  |
|   $\\Tau$   |          $\\tau$          |   Tau   |
| $\\Upsilon$ |        $\\upsilon$        | Upsilon |
|   $\\Phi$   |     $\\phi, \\varphi$     |   Phi   |
|   $\\Chi$   |          $\\chi$          |   Chi   |
|   $\\Psi$   |          $\\psi$          |   Psi   |
|  $\\Omega$  |         $\\omega$         |  Omega  |

</td>
</tbody>
</table>

## Mengensymbole

|           Symbol           |      Symbol Name       |              Bedeutung              |                  Beispiel                  |
|:--------------------------:|:----------------------:|:-----------------------------------:|:------------------------------------------:|
|        $\\{\\,\\}$         |         Menge          |     eine Sammlung von Elementen     |   $A = \\{3,7,9\\}$<br>$B = \\{2,3,9\\}$   |
|        $\\emptyset$        |      leere Menge       |      $\\emptyset = \\{\\,\\}$       |             ein leerer Beutel              |
| $\\{x\\, \vert \\cdots\\}$ |         Menge          | Menge aller $x$<br>für die gilt ... | $\\{x\\,\vert\\,x$ ist eine Primzahl $\\}$ |
|           $\\in$           |     Elementzeichen     |          (ist) Element von          |                 $7 \in A$                  |
|         $\\notin$          |     Elementzeichen     |       (ist) nicht Element von       |                $7 \notin B$                |
|          $\\cap$           |  geschnitten; Schnitt  |        In $A$ **und** in $B$        |          $A \\cap B = \\{3,9\\}$           |
|          $\\cup$           | vereinigt; Vereinigung |       In $A$ **oder** in $B$        |        $A \\cup B = \\{2,3,7,9\\}$         |
|             \              |    ohne; Differenz     |     In $A$ **und nicht** in $B$     |         $A \\setminus B = \\{7\\}$         |

## Aussagensymbole

|       Symbol       |          Bedeutung           |                            Beispiel                             |
|:------------------:|:----------------------------:|:---------------------------------------------------------------:|
|      $\\land$      |             und              | $A \\cap B := \\{x\\,\vert\\,x \\in A \\,\\land\\, x \\in B\\}$ |
|      $\\lor$       |             oder             | $A \\cup B := \\{x\\,\vert\\,x \\in A \\,\\lor\\, x \\in B\\}$  |
|     $\\veebar$     |        entweder oder         |     $A \\triangle B := (A \\cup B) \\setminus (A \\cap B)$      |
|      $\\lnot$      |            nicht             |              $x \\notin A \\iff \\lnot(x \\in A)$               |
| $\\Longrightarrow$ | wenn ... dann; aus ... folgt |        $x \\in A \\setminus B \\Longrightarrow x \\in A$        |
|     $\\forall$     | für alle ... gilt; jede(r,s) |             $\\forall x \\in A : x \\in A \\cup B$              |
|     $\\exist$      |           es gibt            |              $\\exist x \\in A : x \\in A \\cap B$              |
|     $\\exist!$     |    es gibt nur eine(r,s)     |           $\\exist! x \\in A : x \\in A \\setminus B$           |