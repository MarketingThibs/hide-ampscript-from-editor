# Hide AMPscript in Content Builder or Cloud Pages editor 

When you're not doing send previews, big AMPscript code blocks can make your email un-readable. 
You can easily hide a block using the following : 

```html
<!== ==>
```

But if you save this one into a free form this might transform it but still hide the code.

You can also do the following 

```vbscript
%%[
/* My ampscript comment that describes the block <div style="display:none"> */
here goes the code
/*</div>*/ 
]%%
```
