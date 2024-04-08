# Multiplexer4to1
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)
# Code
```
module mux(a,b,c,d,s0,s1,y);
input a,b,c,d,s0,s1;
output y;
assign y=s1 ?(s0?d:c):(s0?b:a);
endmodule
```

# Output
![318371690-756b0dcf-db59-4ccb-9c00-d1f355ae740a](https://github.com/Vijayananthperumal22/Multiplexer4to1/assets/107705127/d04b066c-0d96-41ac-81de-ba62b8fbb194)
