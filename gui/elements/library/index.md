---
title: GUI Element Library
layout: layout.html
---

# GUI Element Library

Elements are speparated into these categories:

1. [Containers](#containers)
2. [Media](#media)
3. [Input](#input)
4. [Views](#views)
5. [Misc](#misc)

## Containers

### gui-vbox

A container with vertical (rows) that you can shrink/expand, also make content expand or fill.

![gui-vbox](/manual/images/gui/gui-vbox.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>gui-vbox-container</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-vbox">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-hbox

A container with horizontal (columns) that you can shrink/expand, also make content expand or fill.

![gui-hbox](/manual/images/gui/gui-hbox.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>gui-hbox-container</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-hbox">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-paned-view

A container with horizontal (columns) that you can shrink/expand, also make content expand or fill.

![gui-paned-view](/manual/images/gui/gui-paned-view.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>gui-paned-view-container</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-paned-view">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-tabs

A tabbed container.

![gui-tabs](/manual/images/gui/gui-tabs.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>gui-tab-container</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-tabs">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-toolbar

A container for holding buttons, etc.

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>all</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.toolbar">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-button-bar

Works like a toolbar, but is made for holding buttons with user-defined position(s).

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>all</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.button-bar">Overview</a></td>
    </tr>
  </tbody>
</table>

---

## Media

### gui-image
A normal image.

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-image">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-canvas
A paintable image (no actual painting included)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-canvas">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-audio
Play sounds or music.

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-audio">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-video
Display a video.

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-video">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-iframe
Display a iframe.

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-iframe">Overview</a></td>
    </tr>
  </tbody>
</table>

---

## Input

### gui-label
Display a normal text label.

![gui-label](/manual/images/gui/gui-label.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-label">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-button
A button made for clicking!

![gui-button](/manual/images/gui/gui-button.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-button">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-switch
A button, but works more like a light-switch.

![gui-switch](/manual/images/gui/gui-switch.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-switch">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-radio
A radio button.

![gui-radio](/manual/images/gui/gui-radio.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-radio">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-checkbox
A checbox.

![gui-checkbox](/manual/images/gui/gui-checkbox.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-checkbox">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-select
A dropdown input.

![gui-select](/manual/images/gui/gui-select.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-select">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-select-list
A selectable list.

![gui-select-list](/manual/images/gui/gui-select-list.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-select-list">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-slider
A slider for giving a variable input.

![gui-slider](/manual/images/gui/gui-slider.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-slider">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-text
A text entry box.

![gui-text](/manual/images/gui/gui-text.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-text">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-password
A password entry box.

![gui-password](/manual/images/gui/gui-password.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-password">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-textarea
A big text entry area.

![gui-textarea](/manual/images/gui/gui-textarea.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-textarea">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-richtext
A big text entry area, with support for HTML.
<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-richtext">Overview</a></td>
    </tr>
  </tbody>
</table>

---

## Views

### gui-tree-view
A view with tree display (nested).

![gui-tree-view](/manual/images/gui/gui-tree-view.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-tree-view">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-icon-view
A view with icon display.

![gui-icon-view](/manual/images/gui/gui-icon-view.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-icon-view">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-list-view
A view with list display.

![gui-list-view](/manual/images/gui/gui-list-view.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-list-view">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-file-view
A combination of all views above, with direct connection to the VFS. For file browsing.
<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-file-view">Overview</a></td>
    </tr>
  </tbody>
</table>

---

## Misc

### gui-progressbar
A box for showing progress.

![gui-progress](/manual/images/gui/gui-progress.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-progress-bar">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-color-swatch
A box for selecting colors from a palette.

![gui-color-swatch](/manual/images/gui/gui-color-swatch.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-color-swatch">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-menu-bar
A bar for showing menus with.

![gui-menu-bar](/manual/images/gui/gui-menu-bar.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>gui-menu-bar-entry</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-menu-bar">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-menu
A menu box.
<table class="reference">
  <tbody>
    <tr>
      <td>Supported Parents</td>
      <td>gui-menu-bar-entry</td>
    </tr>
    <tr>
      <td>Allowed Children</td>
      <td>gui-menu-entry</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-menu">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-statusbar
A bar for showing statuses.
<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-statusbar">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-file-upload
Creates a button for uploading files.
<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-file-upload">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-input-modal
A textbox with an attached button designed for bringing up dialogs to set values.

![gui-input-modal](/manual/images/gui/gui-input-modal.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-input-modal">Overview</a></td>
    </tr>
  </tbody>
</table>

### gui-color-box
A button, but instead of text shows the color assigned.

![gui-color-box](/manual/images/gui/gui-color-box.png)

<table class="reference">
  <tbody>
    <tr>
      <td>Allowed Children</td>
      <td>none</td>
    </tr>
    <tr>
      <td>API Reference</td>
      <td><a href="/doc/client/OSjs.GUI.Elements.html#.gui-color-box">Overview</a></td>
    </tr>
  </tbody>
</table>
