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



Let's do an easy model swap for two characters in Season 1. So let's say you want to change Lilly into Kenny. 

What I usually do is make two folders to organize everything. One named Lilly, and one named Kenny.
For both Lilly and Kenny I make three subfolders: data, txmesh, anichore to keep everything separate.

![image](https://github.com/user-attachments/assets/03230ccd-cd1c-4d6d-a453-bb5ac54da6f8)


So open Telltale Explorer and open WDC_pc_ProjectSeason1_data.ttarch2. In the search bar type kenny and go to Save All Files,  Save all visible files (Raw Dump). Save these to Kenny's data folder. 

Then search Lilly and do the same but save all the visible files to Lilly's data folder.

Do this same process for the txmesh and anichore ttarch2 files for episode 1 so that the files are in their appropriate folders. Files from txmesh.ttarch2 into their respective txmesh folders, anichore.ttarch2 files in their respective folders.

So to swap Lilly into Kenny you must first look at her prop file.

Males usually for Season 1/2 start with sk54_, females start with sk55_, and children start with sk56_
Lilly's prop file is named sk55_lilly.prop
So try to use Kenny's data folder as a reference to rename this file. As we can see her prop name is sk54_kenny.prop

So we rename sk55_lilly.prop to sk54_kenny.prop.

Next we want to swap the ptable files which control their mouth movements. 

As we can see Lilly has fewer ptable files than Kenny

![image](https://github.com/user-attachments/assets/bd013fdf-e6b6-4df8-b6ef-0f8a241b124a)


That's not a problem. If a character doesn't have as many ptable files or anm files as another character, we can simply copy and paste to make up the difference.
So for example, Lilly only has HappyA.ptable, while Kenny has HappyA, HappyB and Happy C. First make three copies of Lilly's HappyA.ptable.

![image](https://github.com/user-attachments/assets/255134cc-38fa-4fe1-8021-2a66fe6efc42)

Then you rename them as they are in Kenny's folder, using Kenny's folder as a reference. 

![image](https://github.com/user-attachments/assets/2620efad-c22b-45d9-b51f-bf74673fe156)


This is pretty much the same deal for swapping the .anm files for two characters since sometimes characters may have more files than others.
Another problem you may encounter is this:
You may also notice Lilly doesn't have a Surprise.ptable file like Kenny, you can use her Fear.ptable files instead as they convey similar emotions. You can use whatever files you feel are appropriate or closest.







## Rehashed Models 
Some characters reuse the same animations so you can simply swap their prop files only without all the hassle. 

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
