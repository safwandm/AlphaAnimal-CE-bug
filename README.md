# AlphaAnimal-CE-bug

Exception ticking AA_Nightling63762 (at (179, 0, 146)): System.NullReferenceException: Object reference not set to an instance of an object
  at CombatExtended.Verb_LaunchProjectileCE.TryCastShot () [0x00026] in <818ae093499a4140b0159bf9e706c495>:0 
  at CombatExtended.Verb_ShootCE.TryCastShot () [0x00028] in <818ae093499a4140b0159bf9e706c495>:0 
  at (wrapper dynamic-method) Verse.Verb.Verse.Verb.TryCastNextBurstShot_Patch0(Verse.Verb)
  at Verse.Verb.WarmupComplete () [0x00013] in <c36f9493c9844ddaa7fb5c788416098f>:0 
  at CombatExtended.Verb_LaunchProjectileCE.WarmupComplete () [0x000c1] in <818ae093499a4140b0159bf9e706c495>:0 
  at CombatExtended.Verb_ShootCE.WarmupComplete () [0x000ad] in <818ae093499a4140b0159bf9e706c495>:0 
  at Verse.Stance_Warmup.Expire () [0x0000a] in <c36f9493c9844ddaa7fb5c788416098f>:0 
  at Verse.Stance_Busy.StanceTick () [0x00017] in <c36f9493c9844ddaa7fb5c788416098f>:0 
  at (wrapper dynamic-method) Verse.Stance_Warmup.Verse.Stance_Warmup.StanceTick_Patch1(Verse.Stance_Warmup)
  at Verse.Pawn_StanceTracker.StanceTrackerTick () [0x00018] in <c36f9493c9844ddaa7fb5c788416098f>:0 
  at Verse.Pawn.Tick () [0x00067] in <c36f9493c9844ddaa7fb5c788416098f>:0 
  at Verse.TickList.Tick () [0x0015c] in <c36f9493c9844ddaa7fb5c788416098f>:0 
Verse.Log:Error(String, Boolean)
Verse.TickList:Tick()
Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2(TickManager)
Verse.TickManager:TickManagerUpdate()
Verse.Game:Verse.Game.UpdatePlay_Patch2(Game)
Verse.Root_Play:Verse.Root_Play.Update_Patch1(Root_Play)
