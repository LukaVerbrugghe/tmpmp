# tmpmp
basic.forever(function() {
    basic.pause(100);
    tegenligger0 = game.createSprite(0,0)
    basic.pause(Math.randomRange(0,5000))
    while(spelBezig){
        if(tegenligger0.get(LedSpriteProperty.Y) == 4){
            if(speler.isTouching(tegenligger0)){
                spelBezig = false;
            }
            else{
                score += 1;
                tegenligger0.set(LedSpriteProperty.Y, 0)
                basic.pause(Math.randomRange(0, 5000))
            }
        }
        else{
            tegenligger0.change(LedSpriteProperty.Y,1)
            basic.pause(wachttijd)
        }
    }
})

basic.forever(function () {
    basic.pause(100);
    tegenligger1 = game.createSprite(1, 0)
    basic.pause(Math.randomRange(0, 5000))
    while (spelBezig) {
        if (tegenligger1.get(LedSpriteProperty.Y) == 4) {
            if (speler.isTouching(tegenligger1)) {
                spelBezig = false;
            }
            else {
                score += 1;
                tegenligger1.set(LedSpriteProperty.Y, 0)
                basic.pause(Math.randomRange(0, 5000))
            }
        }
        else {
            tegenligger1.change(LedSpriteProperty.Y, 1)
            basic.pause(wachttijd)
        }
    }
})

basic.forever(function () {
    basic.pause(100);
    tegenligger2 = game.createSprite(2, 0)
    basic.pause(Math.randomRange(0, 5000))
    while (spelBezig) {
        if (tegenligger2.get(LedSpriteProperty.Y) == 4) {
            if (speler.isTouching(tegenligger2)) {
                spelBezig = false;
            }
            else {
                score += 1;
                tegenligger2.set(LedSpriteProperty.Y, 0)
                basic.pause(Math.randomRange(0, 5000))
            }
        }
        else {
            tegenligger2.change(LedSpriteProperty.Y, 1)
            basic.pause(wachttijd)
        }
    }
})

basic.forever(function () {
    basic.pause(100);
    tegenligger3 = game.createSprite(3, 0)
    basic.pause(Math.randomRange(0, 5000))
    while (spelBezig) {
        if (tegenligger3.get(LedSpriteProperty.Y) == 4) {
            if (speler.isTouching(tegenligger3)) {
                spelBezig = false;
            }
            else {
                score += 1;
                tegenligger3.set(LedSpriteProperty.Y, 0)
                basic.pause(Math.randomRange(0, 5000))
            }
        }
        else {
            tegenligger3.change(LedSpriteProperty.Y, 1)
            basic.pause(wachttijd)
        }
    }
})

basic.forever(function () {
    basic.pause(100);
    tegenligger4 = game.createSprite(4, 0)
    basic.pause(Math.randomRange(0, 5000))
    while (spelBezig) {
        if (tegenligger4.get(LedSpriteProperty.Y) == 4) {
            if (speler.isTouching(tegenligger4)) {
                spelBezig = false;
            }
            else {
                score += 1;
                tegenligger4.set(LedSpriteProperty.Y, 0)
                basic.pause(Math.randomRange(0, 5000))
            }
        }
        else {
            tegenligger4.change(LedSpriteProperty.Y, 1)
            basic.pause(wachttijd)
        }
    }
})
