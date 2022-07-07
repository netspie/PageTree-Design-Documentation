# Project Charter

**Working Title**  
&nbsp;&nbsp;&nbsp;&nbsp;UTreeList

**Project Leader**  
&nbsp;&nbsp;&nbsp;&nbsp;Dariusz Luśnia

**Project Description**  
&nbsp;&nbsp;&nbsp;&nbsp;Graphical user interface library for Unity3D engine. It is supposed to consist of various, reusable graphical lists and list elements for hierarchical and interconnected data manipulation, organization and presentation.

## Purposes
**Main**  
&nbsp;&nbsp;&nbsp;&nbsp;To provide a common basis for another application's features which are sharing same functionalities. It's needed to solve the original application domain problems easily.

**Other**  
&nbsp;&nbsp;&nbsp;&nbsp;\- To serve as a portfolio  
&nbsp;&nbsp;&nbsp;&nbsp;\- To enhance software enginnering skills  
&nbsp;&nbsp;&nbsp;&nbsp;\- To help others  

## Essential Requirements

### Functionalities

Create/Remove sibling or child item  
Edit item data  
Reorder/Move item  
Expand/Collapse item  
  
### Qualities 

*Extendability*  
&nbsp;&nbsp;&nbsp;&nbsp;New custom UI elements should be easily added to existing list items (dropdowns, images, backgrounds, texts, buttons etc.)  

*Modifiability*  
&nbsp;&nbsp;&nbsp;&nbsp;UI items should allow for easy enable or disable its subelements/subfeatures while developing for quick customization  

*Testability*  
&nbsp;&nbsp;&nbsp;&nbsp;Code structured in such a way, so it is easy to make automated tests for modification safety  

*UI Usability*  
&nbsp;&nbsp;&nbsp;&nbsp; Resizability - when resizing/editing time while development it should be smartly fit

*Performance*  
&nbsp;&nbsp;&nbsp;&nbsp; Quick list presentation and rebuild after modification

**Out of scope**  

Following qualities may be introduced in the future, but for a minimal product might be omitted right now, however it is important to structure project in such a way, so it is easy to extend.  

*User Error Protection*  
&nbsp;&nbsp;&nbsp;&nbsp;Inform about potentially unsafe operations (exit, delete data/state/save, items)  

*Performance*  
&nbsp;&nbsp;&nbsp;&nbsp;Large number of items instantiation  

*Content Presentation*  
&nbsp;&nbsp;&nbsp;&nbsp;Preserve too many items presented at once  

*Navigation/Undo/Redo*  
&nbsp;&nbsp;&nbsp;&nbsp;Remembering user actions - it actually should be in scope of different project  

*Feedback Mechanism*  
&nbsp;&nbsp;&nbsp;&nbsp;Reloading animations, Popups, Error Handling   

*Other*  
&nbsp;&nbsp;&nbsp;&nbsp;Localization, Responsiveness  

## Preliminary Constraints
**Time**  
Minimal viable product should be delivered quickly, so the work on solving original domain problems is started as early as possible.  
The rest of potential features can be developed later while original application is already in use.

## Deliverables
\- Easily importable, independent assets bundle. Its initial form depends on delivery time, but eventually could be a Unity package available in Github.  
\- Design documentation of the project available in separate Github repository.

## Risks
- Too much focus on documentation   

  *Potential Solution*  
  Parallel development and documentation.
  
- Too little qualities described and future functions not foreseen  

  *Potential Solution*  
  Intense brainstorm sessions, existing market exploration for inspiration  
  
## Team
Dariusz Luśnia  
*Project Management, Software Engineering and Design*  

There is possibility to seek for other team member, but after first version of the product delivered.


 
