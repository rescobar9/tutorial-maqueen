# Tutorial-Maqueen

## Step 1
From the ``||Logic:Logic||``section on the left side menu, drag an ``||Logic:if-then-else||`` block inside the ``||Basic:Forever||`` block.
```blocks

basic.forever(function (){
if (true) {
    	
    } else {
    	
    }
})
```

## Step 2
From the ``||Logic:Logic||`` section on the left side menu, drag a ``||Logic:  and  ||`` block and replace the ``||Logic:true||`` block.
```blocks
basic.forever(function () {
    if ( false && false) {
    	
    } else {
    	
    }
})
```

## Step 3
From the ``||Logic:Logic||`` section on the left side menu, drag a ``||Logic:if-then ||`` block and place it  inside the  ``||Logic:if-then-else||`` block.
```blocks

basic.forever(function () {
    if (true) {
        if (true) {
        	
        }
    } else {
    	
    }
})
```

## Step 4
From the ``||Logic:Logic||`` section on the left side menu, drag a ``||Logic: Blank and Blank ||`` block and replace the ``||Logic:true||`` block.
```blocks

basic.forever(function () {
    if (true) {
        if (true) {
        	
        }
    } else {
    	
    }
})
```

## Step 5
From the ``||Logic:Logic||`` section on the left side menu, drag a ``||Logic: Blank and Blank ||`` block and replace the ``||Logic:true||`` block.
```blocks

basic.forever(function () {
    if (true) {
        if (true) {
        	
        }
        if (true) {
        	
        }
    } else {
    	
    }
})
```