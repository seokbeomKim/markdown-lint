---
title: MD027 - Multiple spaces after blockquote symbol
tags:  [blockquote, whitespace, indentation]
alias: no-multiple-space-blockquote
---

This rule is triggered when blockquotes have more than one space after the
blockquote (`>`) symbol:

    >  This is a block quote with bad indentation
    >  there should only be one.

To fix, remove any extraneous space:

    > This is a blockquote with correct
    > indentation.

