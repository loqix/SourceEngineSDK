Setup like this:

      void SetupIndexes()
      {
      	using namespace indexes;
      	//Client
      	GetAllClasses = 8;
      	
      	//Engine
      	GetScreenSize = 5;
      	GetPlayerInfo = 8;
      	GetLocalPlayer = 12;
      	ClientCmd = 108;
      	SetViewAngles = 19;
      	GetViewAngles = 18;
      	WorldToScreenMatrix = 37;
      
      	//ClientEntList
      	GetClientEntity = 3;
      	GetHighestEntityIndex = 8;
      	GetClientEntityFromHandle = 7;
      
      	//Surface
      	SetDrawColor = 15;
      	DrawFilledRect = 16;
      	DrawOutlinedRect = 18;
      	DrawLine = 19;
      	SCreateFont = 71;
      	SetFontGlyphSet = 72;
      	DrawSetTextFont = 23;
      	DrawSetTextColor = 25;
      	DrawSetTextPos = 26;
      	DrawPrintText = 28;
      
      	//ModelInfo
      	GetStudioModel = 29;
      }
