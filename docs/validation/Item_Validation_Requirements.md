# Microsoft Fabric Item Validation - Test Cases

> **Document Version:** 2025-10-16  
> **Status:** Official Validation Guidelines

This document outlines all validation requirements for Microsoft Fabric items (workload-specific artifacts).

---

## General Requirements

General requirements for item naming, icons, and basic metadata

---

### 1.1 - Has a clear name

Item must have a clear, descriptive display name that helps users understand its purpose and type

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.2 - Has a clear icon

Item must provide a clear, recognizable icon that visually represents the item type across the Fabric interface

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.2.1 - Has a clear active icon

Item must provide a distinct active state icon to indicate when the item is selected or in focus

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.3 - Has a clear title in create menue

Item must display a clear title in the create menu that matches the item's display name for consistency

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4 - Has a clear subtitle in create menu

Item must provide a concise, informative subtitle in the create menu that describes the item's purpose or key features

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.5 - Item can be be favourited in the "new" menue

Item must support favoriting functionality in the 'new' menu to allow users to quickly access frequently used items

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## Item Creation Flow

Requirements for the item creation experience and workspace integration

---

### 2.1 - Item Creation Experience

Item creation flow must follow Fabric design guidelines providing a consistent, intuitive experience for users

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.2 - Item can be created in Creation Hub

Item must be available for creation through the Fabric Creation Hub for centralized item creation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.3 - Item can be created in the Workspace menue

Item must be available for creation through the workspace '+New' menu for contextual item creation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.4 - Create experience uses default experience or provides no default names

Item creation must either use Fabric's default naming experience or avoid generating default names to prevent workspace clutter

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.5 - Item is persistet in the Workspace

Created items must be immediately persisted and visible in the workspace after creation completes

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.6 - Item is in the multitasking menu and supports the behaviour

Items must appear in the multitasking menu and support switching between multiple open items seamlessly

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.7 - Item creation works under *.powerbi.com as well as *.fabric.microsoft.com

Item creation must function correctly on both powerbi.com and fabric.microsoft.com domains for cross-platform support

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## Trial Experience

Optional trial and sample experiences for items

---

### 3.1.1 - Item implements a sample or trial experience

Item should optionally provide a sample or trial experience to help users explore features before committing

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

## Ribbon & Toolbar

Requirements for the item editor ribbon and toolbar following design guidelines

---

### 3.2.1 - Item editor ribbon exists

Item editor must include a ribbon/toolbar component following Fabric design patterns for consistent navigation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.2 - Item editor ribbon has a "Home" tab

Item editor ribbon must include a 'Home' tab as the primary location for frequently used commands

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.3 - Item Editor ribbon actions are aligned with styleguide

Ribbon actions must follow Fabric style guidelines for button placement, grouping, and visual hierarchy

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.4 - Item Editor ribbon implements a save button / autosave

Item editor should provide either explicit save functionality or autosave to prevent data loss

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.2.5 - Item Editor ribbon Color - follows styleguide

Ribbon colors must follow Fabric style guidelines using approved color tokens and theme support

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.6 - Item Editor ribbon Typography - follows styleguide

Ribbon typography must use Fabric-approved fonts, sizes, and weights for consistent text display

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.7 - Item Editor ribbon Elevation - follows styleguide

Ribbon elevation (shadow/depth) must follow Fabric guidelines to maintain proper visual layering

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.8 - Item Editor ribbon Border radius - follows styleguide

Ribbon border radius must follow Fabric guidelines for consistent rounded corner styling

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.9 - Item Editor ribbon Spacing and layouts - follows styleguide

Ribbon spacing and layout must use Fabric-approved padding, margins, and grid systems for visual consistency

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.2.10 - Item Editor ribbon Tooltips - follows styleguide

Ribbon tooltips must follow Fabric guidelines for content, timing, and placement to aid user understanding

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## Canvas & Editor

Requirements for the item canvas and editor UI components

---

### 3.3.1 - Canvas border - follows styleguide

Canvas border styling must follow Fabric guidelines for color, width, and border radius

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.3.2 - Colors - follows styleguide

Canvas colors should follow Fabric style guidelines using semantic color tokens and theme support

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.3 - Empty states - follows styleguide

Empty states should follow Fabric guidelines providing helpful messaging and clear actions for users

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.4 - Left drawer - follows styleguide

Left drawer panel should follow Fabric guidelines for width, animation, and content organization

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.5 - Bottom Drawer - follows styleguide

Bottom drawer panel should follow Fabric guidelines for height, animation, and content organization

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.6 - Tabs - follows styleguide

Tab components should follow Fabric guidelines for styling, interaction, and active state indication

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.7 - Switch - follows styleguide

Switch/toggle controls should follow Fabric guidelines for size, color, and interaction behavior

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.8 - Left drawer - follows styleguide

Right drawer panel should follow Fabric guidelines for width, animation, and content organization

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 3.3.10 - Buttons

Button components should follow Fabric guidelines for styling, sizing, states, and interaction patterns

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

## Navigation

Requirements for navigation between item views and levels

---

### 3.4.1 - Navigation between main canvas (L1) and L2 must follow guidelines

Navigation between canvas levels (L1 to L2) must follow Fabric guidelines for transitions, breadcrumbs, and back navigation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## Popup Dialogs

Requirements for popup dialogs and modal windows following design guidelines

---

### 4.1.1 - Popup dialog - follows styleguide

Popup dialogs must follow Fabric style guidelines for modal behavior, backdrop, and dismissal patterns

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.2 - Color - follows styleguide

Dialog colors must follow Fabric guidelines using semantic color tokens for backgrounds, text, and borders

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.3 - Typography - follows styleguide

Dialog typography must use Fabric-approved fonts, sizes, and hierarchy for headers, body text, and actions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.4 - Elevation - follows styleguide

Dialog elevation must follow Fabric guidelines to ensure proper visual layering above page content

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.5 - Border radius - follows styleguide

Dialog border radius must follow Fabric guidelines for consistent rounded corner styling across modals

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.6 - Spacing and layouts - follows styleguide

Dialog spacing and layout must use Fabric-approved padding, margins, and content organization patterns

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## Other Requirements

Additional requirements including monitoring, settings, and context menus

---

### 4.2.1 - Monitoring Hub integration

Item should optionally integrate with Fabric Monitoring Hub to expose job execution and performance data

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 4.2.2 - Actions in Workspace need to work

All item actions available in the workspace (rename, delete, share, etc.) must function correctly

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.2.7 - Jobs to be done are set

Item should optionally define job types in the manifest to enable job tracking and monitoring integration

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 4.2.8 - Item Settings are used

Item should optionally implement settings panel for user configuration following Fabric patterns

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 4.2.10 - Context Menu Actions

Item should optionally define custom context menu actions in the manifest for enhanced workspace interaction

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 4.2.11 - Context Menu Actions in workspace are working and usable

All defined context menu actions must function correctly and provide intuitive, accessible user interactions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

---

## Additional Information

### Version History

This document is automatically generated.

---

*Generated by Microsoft Fabric Workload Validation System*  
*© 2025 Microsoft Corporation. All rights reserved.*
