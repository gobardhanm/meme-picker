# Concepts>

    > for of
    > radio and cheackbox inputs
    > getElementByClassName
    > querySelector
    > classList.remove
    > import/export
    > .includes()
    > .filter()

# JS
    > for of:
        Ex: for (let character of characters)

        Here the character is the variable and characters is the array, and each object of characters will be assigned to the characters one at a time.

    > import/export:

        we "import" something from a different file using "export" in that file
        
        Ex: we can "export" a array from a file let say "data.js" using:

            "export const dinnerPartyGuests"

            And we can "import" that array in our file let say "index.js" by:

            "import { dinnerPartyGuests } from '/data.js'"

            ** But we'll still get a error here >> To eliminate that error we have to add 'type="module"' in "HTML" script link as:

                <script src="index.js" type="module"></script> 

    > .inclues() : (A method for cheacking if an array holds a given value?) :

        Ex: 
            const emojis = ['🐥','🐯','🐼']
            console.log(emojis.includes('🐴'))
            
            > Here it will log out true or false according to the statement.
# HTML
    > Radio Inputs
        
        A radio type of input can be achieved by:

            <div class="radio">
                <input 
                type="radio"
                id="ducks"
                value="horses"
                name="choice-radios"
                >
                <label for="horses">5 duck-sized horses</label>
            </div>
 
        ** - Here the "type ="radio"" gives us radio inputs
           
           - We give id accordingly
           
           - Value property is important bcoz it tells us what the radio represents, we can give a desciptive name also.
          
          *- "name" of all the radio should be "same" when we dont want to select multiple input.
          
          - "for" in the label used for selecting the radio by clicking on the label 

# CSS