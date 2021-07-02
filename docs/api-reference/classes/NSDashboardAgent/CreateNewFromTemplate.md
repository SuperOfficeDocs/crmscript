﻿---
uid: crmscript_ref_NSDashboardAgent_CreateNewFromTemplate
title: DashboardTile CreateNewFromTemplate(Integer dashboardTileId, String caption, String description, Integer selectionId, VisibleFor[] visibleFor)
intellisense: NSDashboardAgent.CreateNewFromTemplate
keywords: NSDashboardAgent, CreateNewFromTemplate
so.topic: reference
---

Create new tile from another tile used as template

**Parameters:**
 - **dashboardTileId** Tile template Id
 - **caption** Caption of new tile
 - **description** Description of new tile
 - **selectionId** Selection id of new tile
 - **visibleFor** Who the tile should be visible for

**Returns:** The new tile

```crmscript
NSDashboardAgent agent;
Integer dashboardTileId;
String caption;
String description;
Integer selectionId;
VisibleFor[] visibleFor;
DashboardTile res = agent.CreateNewFromTemplate(dashboardTileId, caption, description, selectionId, visibleFor);
```

