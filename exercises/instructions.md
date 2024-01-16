# Getting Started with LEAF-Writer: Exercises

These exercises will walk you through the steps to perform basic structural, semantic, entity, and note markup using LEAF-Writer. There are five sections:

[1. Set Up](#set-up)  
[2. Exercise 1: Structural Markup](#exercise-1)  
[3. Exercise 2: Other Semantic Markup](#exercise-2)  
[4. Exercise 3: Entity Markup](#exercise-3)  
[5. Exercise 4: Note Markup](#exercise-4)  

The exercises are from a [workshop](https://docs.google.com/presentation/d/10e899QyGt-fN79SzKLckX57Vx_AlDbLA4RfmZ0jE_-U/edit#slide=id.g13ec423ffec_0_0 "workshop slides") given at TEI 2022.

To learn more about marking up documents using LEAF-Writer, watch [LEAF-Writer Tutorial 1](https://www.youtube.com/watch?v=mMGVZte9NbA) and [LEAF-Writer Tutorial 2](https://www.youtube.com/watch?v=nJTtJG7VhWo).


## <a name="set-up"></a>Set Up

You will need a GitHub account to sign into LEAF-Writer and access and work with the exercise files.

1. If you don't have a GitHub account, create one at http://github.com/.
2. Go to the GitHub repository https://github.com/LEAF-VRE/training.
3. Fork the repository (create a copy of it in your personal GitHub account) by selecting __Fork__ on the upper right.
4. Sign in to https://leaf-writer.leaf-vre.org.

## <a name="exercise-1"></a> Exercise 1: Structural Markup

Structural markup provides information about the structure of a document. In this exercise, you will mark up a poem to provide information about its lines and emphasis.

### Tag Lines ###

1. Select __From the Cloud__ to open __exercise1_macavity__ in training\gettingstarted\exercises.
2. Select __Don't Show Again__ in the Editor Mode pop-up.
3. Select the __Image Viewer__ tab on the right to see an image of the print version of the poem.
4. Highlight "Macavity, Macavity, there's no one like Macavity," below line 4.
5. Select __Tags__ on the far left of the ribbon at the top of the screen.
6. Find the `l` (line) tag by typing it into the search box or scrolling down the list of tags.
7. Select the `l` tag from the list and then select __OK__.
8. Try another way of tagging a line — highlight the line text, right click, and then select __Add Tag__, `l`, and __OK__.
9. Add `l` tags to the remaining lines in the poem using both methods.
10. Edit the tags around the first line of the poem, which has been mistakenly tagged as a salutation, by clicking on the line, right clicking on `salute` in the __Markup__ panel on the left, and selecting __Change Tag__ from the dropdown menu, `l`, and __OK__.

### Tag Emphasis ###

11. Highlight "Macavity's not there!" on line 5.
12. Select __Tags__ on the far left of the ribbon at the top of the screen.
13. Find the `emph` (emphasized) tag by typing it into the search box or scrolling down the list of tags.
14. Select the `emph` tag from the list and then select __OK__.
15. Add `emph` tags to all the words italicized in the print version.

As you add tags, you will see them appear in the __Markup__ panel on the left. You can also see raw code in the __Selection__ tab on the right. Using the __Markup__ panel and the __Selection__ tab, see if you can find the tags you added.

## <a name="exercise-2"></a> Exercise 2: Other Semantic Markup

Structural markup is a kind of semantic markup, or markup about what data means rather than its presentation and style. In this exercise, you will mark up a salutation, signatures, and a dateline in a letter.

### Tag a salutation ###

1. Select __From the Cloud__ to open __exercise2_letter-congress__ in training\gettingstarted\exercises.
2. Right click on the first `p` in the Markup pane.
3. Select __Change Tag__ from the dropdown menu.
4. Select `opener` and __OK__.
5. Right click on `opener` in the Markup pane.
6. Select __Tag Inside__ from the dropdown menu.
7. Select `salute` and __OK__.

### Tag signatures and a dateline ###

8. Right click the last `p` in the Markup pane.
9. Select __Change Tag__ from the dropdown menu.
10. Select `closer` and __OK__.
11. Highlight "Elizabeth Cady Stanton."
12. Select __Tags__ on the far left of the ribbon at the top of the screen.
13. Select the `signed` tag from the list and then select __OK__.
14. Add `signed` tags around the other names in the `closer`.
15. Highlight "Dec. 1871" and add a `dateline` tag around it.

## <a name="exercise-3"></a> Exercise 3: Entity Markup

Entity markup allows you to give data, like data about people and places, semantic meaning through the use of standard identifiers (IDs). These IDs can link the same things across your own documents or create interoperability with external data when the same IDs are used by many people (let's work on this :) provide links to LOD stuff or not here?). In this exercise, you will tag people, place, organization, and date entities in a letter.

### Tag a Person ###
1. Select __From the Cloud__ to open __exercise3_letter-congress__ in training\gettingstarted\exercises.
2. Highlight "Elizabeth Cady Stanton." 
3. Select __Tag Person__ in the ribbon (to the right of __Tags__).
4. Under Wikidata, select American writer, suffragist, and women's rights activist and then __Select__.
5. Add a certainty value of __high__ and then select __OK__.

### Tag a Place

6. Highlight "Hartford."
7. Select __Tag Place__ in the ribbon (to the right of __Tag Person__).
8. Under Wikidata, select the city in Connecticut, United States, and then __Select__.
9. Add a certainty value of __high__ and then select __OK__.

### Tag an Organization and Date — Try It for Yourself ###
10. Experiment with tagging the United States "Congress" by using __Tag Organization__ (to the right of __Tag Place__).
11. Experiment with tagging the date of "1871" by using __Tag Date__ (to the right of __Tag Organization__).

## <a name="exercise-4"></a> Exercise 4: Note Markup

LEAF-Writer allows you to add notes to a document, as one way of creating a scholarly apparatus for it. In this exercise, you will add a research note and scholarly notes to a poem.

### Tag a Research Note ###

1. Select __From the Cloud__ to open __exercise4_ebb__ in training\gettingstarted\exercises.
2. Place the cursor at the end of line 5 to add a Research Note there.
3. Select __Tag Note__ in the ribbon and add a note with the Type of Research Note. 
4. Add the Note Text, "I need to doublecheck punctuation of transcription."
5. Select __OK__.

### Tag a Scholarly Note ###

6. Copy the text of the first Scholarly Note at the bottom of the file.
7. Place the cursor at the end of line 1 to add a Scholarly Note there.
8. Select __Tag Note__ in the ribbon and add a note with the Type of Scholarly Note. 
9. Paste the text of first copied scholarly note into the Note Text.
10. Select __OK__. 
11. Add the other two Scholarly Notes at the bottom of the file to the correct lines.
