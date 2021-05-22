# ClauScanner
  1. Parallel Scanner Using thread. 

  2. Most TokenType is STRING. also integer is handled as STRING. so, STRING -> INTEGER (Conversion) is needed.
 

# Text Style 001
    # Paradox Game Save Data Style + line comment ?.
    TokenType : {  }  =   "quoted string"   "quoted \" string \" 123 "   string  # line comment
    
# Text Style 002
    # json-like?
    TokenType : { } : [ ] "quoted string"  "quoted \" string \" 123 "  string  
                /* multi line comment */  // line comment  
                # line comment
                
