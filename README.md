# The-Walking-Dead-Definitive-Model-Swapping
This is a tutorial for the classic model swap method for The Walking Dead Game: The Definitive Series. 

I'll try to explain the basics of modding characters for The Walking Dead The Definitive Series.

There are three kinds of ttarch2 files you'll encounter.

So let's use season 1 for example. For only Season 1 most characters' files are found in these files

WDC_pc_ProjectSeason1_data.ttarch2
WDC_pc_ProjectSeason1_txmesh.ttarch2
WDC_pc_ProjectSeason1_anichore.ttarch2

For Season 2-4 this is how the ttarch2 files will look (Season 2 as an example):

WalkingDead_pc_WalkingDead201_data.ttarch2
WalkingDead_pc_WalkingDead201_txmesh.ttarch2
WalkingDead_pc_WalkingDead201_anichore.ttarch2

So within the data ttarch2 these are the only files you need to worry about:

.prop this contains the general model data
.ptable this controls mouth movements
.skl this is the skeleton of the character

Next, within the txmesh ttarch2 these are the only files you need to worry about:

.d3dmesh this contains the character's model meshes
.d3dtx this contains texture data

Lastly, within the anichore ttarch2 these are the only files you need to worry about:

.anm animation files

So to open these ttarch2 files you will need Telltale Explorer. You can download it here: https://quickandeasysoftware.net/software/telltale-explorer

![image](https://github.com/user-attachments/assets/64591c45-0d84-46e4-a88b-44a2e1df0dce)



Let's do an easy model swap for two characters in Season 1. So let's say you want to change Kenny into Lilly. 

What I usually do is make two folders to organize everything. One named Kenny, and one named Lilly.
For both Kenny and Lilly I make three subfolders: data, txmesh, anichore to keep everything separate.

![image](https://github.com/user-attachments/assets/c64c2f2d-cb51-475b-8edb-3f9a79660e56)

So open Telltale Explorer and open WDC_pc_ProjectSeason1_data.ttarch2. In the search bar type kenny and go to Save All Files,  Save all visible files (Raw Dump). Save these to Kenny's data folder. 

Then search Lilly and do the same but save all the visible files to Lilly's data folder.

Do this same process for the txmesh and anichore ttarch2 files for episode 1 so that the files are in their appropriate folders. Files from txmesh.ttarch2 into their respective txmesh folders, anichore.ttarch2 files in their respective folders.

So to swap Kenny into Lilly you must first look at his prop file.

Males usually for Season 1 start with sk54_, females, sk55_ and children sk56_
Kenny's prop file is named sk54_kenny.prop
So try to use lilly's data folder as a reference to rename this file. As we can see her prop name is sk55_lilly.prop

So we rename sk54_kenny.prop to sk55_lilly.prop.

Next we want to swap the ptable files which control their mouth movements. 

As we can see 








## Rehashed Models 

### TWDG Season 1:

Lee, The Stranger, Nate, Eddie (uses sk54_lee.skl), Bennett, Clyde, Jerry, Lee's brother

Kenny, Hershel, Vernon, Andy St.John, Roman, Justin, Boyd, Leland, Clive

Doug, Cop, Andre, Wyatt, Danny St. John, Shawn Greene, Chuck, Travis(Ben's classmate), David (Ben's teacher)

Lilly, Shel, Katjaa, Carley, Stephanie, Anna Correa, Bonnie, Joyce, Molly, Jolene

Becca

Ben, Larry, Marcus, Chet

Glenn, Vince

Mark, Danny (prisoner)

Brenda St John, Tavia

Omid, Russell



### TWDG Season 2:

Sarah, Michelle

Alvin, Buricko, Tyler

Pete, Carlos, Carver, Winston, Troy, Walter, Victor

Matthew, Omid, Johnny, Arvo, Hank

Kenny, Reggie

Rebecca, Sarita, Natasha, Tisha, Patricia, Vera

Nick, Mike, Ralph

Bonnie, Tavia, Jane, Edith, Katjaa, Lilly

Luke, Vitali, Randy, Lowell

Duck, Gill

Carlos eye files: wd200GM

### TWD Michonne:

PeteMini: Nick

Jonas, Randall, Rashid, sk54_crabber (cam etc), father: Carlos

Paige: Christa

Sam, Gabby, sk55_crabber (janey etc): Lilly

Greg, Oak: Omid

Zachary: Johnny

James, Elodie: S2 Clem

Alex, Colette: S1 Clem

John, Siddiq, Alvin

Berto, Luke

Vanessa, Rebecca


### TWD A New Frontier:

Random New Frontier Thug: Badger, Eli, Hector, Max, Rufus (Driver)

David: Kenny, Conrad, Clint

Javier: Salvador, Badger, Jesus

Young Gabe: Baseball Kid

Clementine, Mariana

Eleanor, Kate, Francine, Edith, Jane

### The Final Season:

Lilly, Dorian, Gina

Tenn, Willy

Louis, Aasim

Eddie: generic male

### Across Seasons:
Clem S3, Clem S4, Mariana

Clint, Abel

MarianaYounger,ClemFlashbackDeleted

Young Gabe, AJ

### The Wolf Among Us

Mirror, Bigby, Jack

Woodsman, Beast and Bluebeard

Holly, Beauty, Nerissa and Faith

Gren, Swineheart and Georgie

Cryer and Jersey Devil 
