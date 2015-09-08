# m8ball
def p1():
    f="c:\\armyb_000\8ball.jpg"
    p=makePicture(f)
    s=makeStyle(sansSerif,bold,18)
    addTextWithStyle(p,93,176, "Better not tell you now",s,white)
    repaint(p)
