
# Table of Contents

1.  [Metadata Syntax](#org2b797b4)
    1.  [Comments](#orgb5f0771)


<a id="org2b797b4"></a>

# Metadata Syntax


<a id="orgb5f0771"></a>

## Comments

Must start on the first column unless these are part of shell/python functions

    # this is a valid comment
        # this is an invalid comment because it does not stat at first column
    HELLO = "WORLD" # this is another valid comment because it is after metadata
    
    
    foo() {
        # this is a valid comment and can start at any column (as in shell)
        echo "foo" # this is also valid (as in shell)
    }
    
    python bar() {
        # this is a valid comment and can start at any column (as in python)
        print("bar") # this is also valid (as in python)
    }

