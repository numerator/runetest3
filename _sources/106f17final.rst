================
Question Bank 1
================

.. mchoice:: 106f17final_6

    .. comp_std:: BPP
        :prim_comp: FUNC05
        :supp_comp: FUNC01, COND02, COND03, DEBUG01

    What is printed when the code below is fun?

    .. code-block:: python

        def add1(n): 
            n=n+1
            if n == 7:
                return 'bingo'
        print( add1(5) )    

    .. 

    - 5

      - There is no return value if n != 7
    
    - 6
    
      - There is no return value if n != 7

    - 7

      - There is no return value if n != 7

    - bingo

      - There is no return value if n != 7

    - None

      + There is no return value if n != 7
    
    - There is an error 

      - There is no return value if n != 7

    - Nothing is printed

      - There is no return value if n != 7


.. activecode:: 106f17final_20

    .. comp_std:: BPP
        :prim_comp: FUNC01
        :supp_comp: VES03, FUNC02, SEQ06, STR03, STR06, DICT02, DICT03, ITER03

    :language: python

    Define a function ``longestXWords(s, x=5)`` that accepts two arguments: 
    a string and returns a list of the x longest words in that string. 
    These words should be unique, meaning that if a word appears more 
    than once in s, it should only appear once in the return value of 
    longestXWords. The list it returns must not be longer than x elements. 
    You may ignore capitalization and punctuation in s. 
    You may also use any strategy for resolving words of equal length. 
    See example calls on the bottom of the page. 

    Hint: To find a list of unique words, one strategy is to iterate over 
    every word and add it to a list of unique words if that word is not 
    already in that list of unique words. You can check if an element is 
    not in a list with the ``not in`` operator: ``2 not in [1,3,5]`` is ``True``.

    ~~~~
    def longestXWords(s, x=5):
        pass

    ====
    #TODO: write tests

