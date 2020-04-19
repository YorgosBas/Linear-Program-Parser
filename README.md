# Linear Program Parser
A Python script to check and parse a Linear Programming Problem of type:
```
min/max z = c1x1 + c2x2 + … + cnxn
st        a11x1 + a12x2 + … + anxn ⊗ b1,
          a21x1 + a22x2 + … + a2nxn ⊗ b2,
                … … … ... … … … … …      ,
          am1x1 + am2x2 + … + amnxn ⊗ bm
end
          
        ⊗ = {≤,=,≥}, c, x∈ℜn, b∈ℜm και A∈ℜmxn
```

## How to run
1. Download Parser.py
2. Write the file name in the code (Example: "Parser_example.txt")
3. Script will generate "parsed_file.txt" containing the matrices of the linear program

## How it works
1. Removes special characters and spaces
2. Checks if linear program is specified correctly and nothing necessary is missing
3. Parses data into matrices
