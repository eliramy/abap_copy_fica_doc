# abap_copy_fica_doc
My sophisticated ABAP Program to copy FICA doc

1) Only see file: FKK_DOCUMENT_COMPLETE.txt
How i did the enhancement why i needed to enhance the function
is the line:
CALLER-ID = 'SIMR'. " -> This ID open fields to edit.


2) Even if i open alot of fields some fields are disable to change.
That why there's program file: YCD_COPY_DOC.txt

To fill the fields which aren't able to edit
and transfer them to function FKK_DOCUMENT_COMPLETE.

Finally Enjoy from this solution :)
 
