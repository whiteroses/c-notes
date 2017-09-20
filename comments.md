# Comments


* To comment out code that contains block comments (`/* */`), use a conditional preprocessor directive:

      # if 0
      /* */
      # endif

* The preprocessor replaces each comment with a space, e.g. `min/*comment*/Value` becomes `min Value`.
