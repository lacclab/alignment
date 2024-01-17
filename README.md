# alignment
OneStop project- Alignment
# Files Description:
1. playground.ipynb: Code file, is used to separate the texts into paragraphs and display them.
2. aligned.csv: used in the code file.
3. texts.csv: used in the code file.
4. aligned.xlsx: this file contains a table with the aligned sentences.

# aligned.xlsx:
in this file, I aligned the sentences from elementary and advanced texts.
let's explain what each column means:
1. **text_id:** This is the unique serial number assigned to each paragraph. Both elementary and advanced paragraphs may share the same serial number.
2. **ele_id:** This number represents the position of the elementary sentence within its respective paragraph.
3. **Text Ele Sentence:** This column contains the actual text of the elementary sentence.
4. a**dv_id:** This number signifies the position of the advanced sentence within its respective paragraph.
5. **Text Adv Sentence:** This column contains the actual text of the advanced sentence.
6. **alignment:** The number on the right side of this column indicates the ID of the elementary sentence that aligns with the advanced sentence, the comma separates the two IDs. To clarify, it denotes the corresponding elementary sentence that pairs with the advanced sentence. If there is no suitable alignment, the square brackets "[]" will only contain a comma, followed by the ID of the sentence that has no alignment. 
