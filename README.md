# KpengScoreForJudge
一个小巧的评分控件 可以作为显示也可以作为评分控件 只需要几行就能集成 

   KpengScoreForJudge *judge =[[KpengScoreForJudge alloc] initWithFrame:CGRectMake(100, 250, 300, 100)];

    judge.backgroundColor =[UIColor redColor];

    judge.needMoveTouch =YES;

    [self.view addSubview:judge];

    judge.fillColor =[UIColor blueColor];

    judge.scoreRefersh = ^(CGFloat rate) {

        NSLog(@"%f---✨数",rate);

    };
