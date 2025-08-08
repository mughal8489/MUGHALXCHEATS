# MUGHALXCHEATS


# BUTTON CODE FOR AIMBOT

    Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
     MemMughal.OpenProcess(proc);

     MemMughal.OpenProcess(Convert.ToInt32(MXC));
 
     IEnumerable<long> longs = await MemMughal.AoBScan2(("Scan Value"), true, true);
 
    if (longs == null)
         notificationLabel.Text = "No Address Found";
 
     foreach (long num in longs)
    {
         string str = num.ToString("X");
         {
             Byte[] originalBytes = MemMughal.AhReadMeFucker((num + First Offset).ToString("X"), 4);
 
             originalValues.Add(num, originalBytes);
 
             Byte[] valueBytes = MemMughal.AhReadMeFucker((num + Second Offset).ToString("X"), 4);
 
 
             MemMughal.WriteMemory((num + First Offset).ToString("X"), "int", BitConverter.ToInt32(valueBytes, 0).ToString());
 
         }
         notificationLabel.Text = "Aimbot Drag Done";
         notificationLabel.ForeColor = Color.Blue;
        
 
     }
    }


# THESE CODES FOR MIRZA MEMORY BOTH BUTTON AIMBOT AND OTHER BUTTON

    Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
    Memlib.OpenProcess(proc);
    var enumerable = await Memlib.AoBScan("Scan VAlue", true, true, string.Empty);
    GTC = "0X" + enumerable.FirstOrDefault().ToString();
    foreach (long num in enumerable)
    {
      Memlib.WriteMemory(num.ToString("X"), "Bytes", "Replace Value", string.Empty, null);
      
    }
  
    status.Text = "Applied successfully";


# INJECTING METHOD  OF AIMBOT BUTTON

    Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
    Memlib.OpenProcess(proc);

    Memlib.OpenProcess(Convert.ToInt32(PID));

    IEnumerable<long> longs = await Memlib.AoBScan2(("FF FF FF FF 00 00 00 00 00 00 00 00 00 00 00 00 ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 A5 43 00 00 00 00 ?? ?? ?? ?? 00 00 00 00 00 00 00 00 ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ?? ?? ?? ?? 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 80 BF"), true);

    if (longs == null)
    label5.Text = "No Address Found";

    foreach (long num in longs)
    {
       string str = num.ToString("X");
       {
             Byte[] originalBytes = Memlib.AhReadMeFucker((num + 0x5c).ToString("X"), 4);

        originalValues.Add(num, originalBytes);

        Byte[] valueBytes = Memlib.AhReadMeFucker((num + 0x60).ToString("X"), 4);


        Memlib.WriteMemory((num + 0x5c).ToString("X"), "int", BitConverter.ToInt32(valueBytes , 0).ToString());

    }
    label3.Text = "Aimbot Done";
    label3.ForeColor = Color.AliceBlue;
    }


# THESE CODES FOR MUGHAL MEMORY
# INJECTING METHOD OF EVERY BUTTON

    Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
    MemMughal.OpenProcess(proc);
    var enumerable = await MemMughal.AoBScan2("Scan Value", true, true, string.Empty);
    MXC = "0X" + enumerable.FirstOrDefault().ToString();
    foreach (long num in enumerable)
    {
    MemMughal.WriteMemory(num.ToString("X"), "Replace Value", "Replace Value", string.Empty, null);

    }
    // Simulate holding for 10 Seconds (10000 milliseconds)
    await Task.Delay(10000); // 10 seconds delay


    notificationLabel.Text = "Inject";


# CODE OF MEMORY.DLL

    if (Process.GetProcessesByName("HD-Player").Length == 0)
    {
    //Type Here Emulator not found Status
    Console.Beep(240, 300);
    }
    else
    {
    //Type Here Waiting Status

    string search = "Scan Value";
    string replace = "Replace Value";

    bool k = false;
    mughal.OpenProcess("HD-Player");

    int i2 = 22000000;
    IEnumerable<long> wl = await mughal.AoBScan(search, writable: true, true);
    string u = "0x" + wl.FirstOrDefault().ToString("X");
    if (wl.Count() != 0)
    {
        for (int i = 0; i < wl.Count(); i++)
        {
            i2++;
            mughal.WriteMemory(wl.ElementAt(i).ToString("X"), "bytes", replace);
        }
        k = true;
    }

    if (k == true)
    {
        Console.Beep(400, 300);
        //Type Here Code Inject Success Status
        notificationLabel.Text = "Inject";
        
    }
    else
    {
        //Type Here Code Inject Faild Status
        Console.Beep(240, 300);
        notificationLabel.Text = "Failed";
    }
    }

# Connect Method Of Memory
# USING MEMORY
# Mem mughal = new Mem();


# DLL INJECTING METHOD

    private static void ExtractEmbeddedResource(string resourceName, string outputPath)
    {
    Assembly executingAssembly = Assembly.GetExecutingAssembly();

    // Get the embedded resource stream
    using (Stream resourceStream = executingAssembly.GetManifestResourceStream(resourceName))
    {
        if (resourceStream == null)
        {
            throw new ArgumentException($"Resource '{resourceName}' not found.");
        }

        // Read the embedded resource and save it to the specified path
        using (FileStream fileStream = new FileStream(outputPath, FileMode.Create))
        {
            byte[] buffer = new byte[resourceStream.Length];
            resourceStream.Read(buffer, 0, buffer.Length);
            fileStream.Write(buffer, 0, buffer.Length);
        }
    }
    }

    [DllImport("kernel32.dll", SetLastError = true)]
    static extern IntPtr OpenProcess(uint processAccess, bool bInheritHandle, int processId);

    [DllImport("kernel32.dll", SetLastError = true)]
    static extern IntPtr GetProcAddress(IntPtr hModule, string lpProcName);

    [DllImport("kernel32.dll", SetLastError = true)]
    static extern IntPtr GetModuleHandle(string lpModuleName);

    [DllImport("kernel32.dll", SetLastError = true)]
    static extern IntPtr VirtualAllocEx(IntPtr hProcess, IntPtr lpAddress, IntPtr dwSize, uint flAllocationType, uint flProtect);

    [DllImport("kernel32.dll", SetLastError = true)]
    static extern bool WriteProcessMemory(IntPtr hProcess, IntPtr lpBaseAddress, byte[] lpBuffer, uint nSize, out IntPtr lpNumberOfBytesWritten);

    [DllImport("kernel32.dll")]
    static extern IntPtr CreateRemoteThread(IntPtr hProcess, IntPtr lpThreadAttribute, IntPtr dwStackSize, IntPtr lpStartAddress, IntPtr lpParameter, uint dwCreationFlags, IntPtr lpThreadId);

    const uint PROCESS_CREATE_THREAD = 0x2;
    const uint PROCESS_QUERY_INFORMATION = 0x400;
    const uint PROCESS_VM_OPERATION = 0x8;
    const uint PROCESS_VM_WRITE = 0x20;
    const uint PROCESS_VM_READ = 0x10;

    const uint MEM_COMMIT = 0x1000;
    const uint PAGE_READWRITE = 4;

# BUTTON CODE

    string processName = "HD-Player"; // Specify your target process name
    string dllResourceName = "Project Name.Dll Name"; // Correct resource name

    // Extract the embedded msdrmi.dll to a temporary file
    string tempDllPath = Path.Combine(Path.GetTempPath(), "Dll Name");
    ExtractEmbeddedResource(dllResourceName, tempDllPath);

    Console.WriteLine($"DLL extracted successfully to: {tempDllPath}");


    Process[] targetProcesses = Process.GetProcessesByName(processName);
    if (targetProcesses.Length == 0)
    {
    Console.WriteLine($"Waiting for {processName}.exe...");
    }
    else
    {
    Process targetProcess = targetProcesses[0];
    IntPtr hProcess = OpenProcess(PROCESS_CREATE_THREAD | PROCESS_QUERY_INFORMATION | PROCESS_VM_OPERATION | PROCESS_VM_WRITE | PROCESS_VM_READ, false, targetProcess.Id);

    IntPtr loadLibraryAddr = GetProcAddress(GetModuleHandle("kernel32.dll"), "LoadLibraryA");
    IntPtr allocMemAddress = VirtualAllocEx(hProcess, IntPtr.Zero, (IntPtr)tempDllPath.Length, MEM_COMMIT, PAGE_READWRITE);

    IntPtr bytesWritten;
    WriteProcessMemory(hProcess, allocMemAddress, System.Text.Encoding.ASCII.GetBytes(tempDllPath), (uint)tempDllPath.Length, out bytesWritten);

    CreateRemoteThread(hProcess, IntPtr.Zero, IntPtr.Zero, loadLibraryAddr, allocMemAddress, 0, IntPtr.Zero);

    Console.Beep(240, 300);
    //Type Here Chams Is Already Injected or code invaible
    
    }


# CODE FOR AIMBOT BUTTON

if (Process.GetProcessesByName("HD-Player").Length == 0)
{
    notificationLabel.Text = "Emulator Not Found!!, Open Emulator First";
}
else
{
   
    Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
    mughal.OpenProcess(proc);

    {
        notificationLabel.Text = "Wait To Inject Aimbot";
    }


    var result = await mughal.AoBScan("Scan Value", true);

    
    if (result != null && result.Any())
    {
        
        var CurrentAddress = result.First();

        
        Int64 Enderecoleitura = CurrentAddress + offset;
        Int64 EndercoEscrita = CurrentAddress + offset;



        
        var Read = mughal.ReadMemory<int>(Enderecoleitura.ToString("X"));

        
        mughal.WriteMemory(EndercoEscrita.ToString("X"), "int", Read.ToString());
        // Beep to indicate success
        Console.Beep(400, 300);

        // Update the notification label
        notificationLabel.Text = "AimBot Success";
       
    }
    else
    {
        // Update the notification label if no match is found
        notificationLabel.Text = "AimBot Failed";
    }
    }



##3 INTERNET CODE

    public void ExecuteCommand(string command)
    {
    ProcessStartInfo psi = new ProcessStartInfo("cmd.exe")
    {
        RedirectStandardInput = true,
        RedirectStandardOutput = true,
        RedirectStandardError = true,
        UseShellExecute = false,
        CreateNoWindow = true
    };

    using (Process process = new Process { StartInfo = psi })
    {
        process.Start();

        // Write the command to the command prompt
        process.StandardInput.WriteLine(command);
        process.StandardInput.Flush();
        process.StandardInput.Close();

        // Wait for the command to finish
        process.WaitForExit();
    }
    }

# BLOCK INTERNET BUTTON CODE

     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=in action=block profile=any program=\"C:\\Program Files\\BlueStacks_nxt\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=out action=block profile=any program=\"C:\\Program Files\\BlueStacks_nxt\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=in action=block profile=any program=\"C:\\Program Files\\BlueStacks\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=out action=block profile=any program=\"C:\\Program Files\\BlueStacks\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=in action=block profile=any program=\"C:\\Program Files\\BlueStacks_msi2\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=out action=block profile=any program=\"C:\\Program Files\\BlueStacks_msi2\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=in action=block profile=any program=\"C:\\Program Files\\BlueStacks_msi5\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall add rule name=\"TemporaryBlock2\" dir=out action=block profile=any program=\"C:\\Program Files\\BlueStacks_msi5\\HD-Player.exe");
     this.notificationLabel.Text = "INJECT";
     Console.Beep();

# UNBLOCK INTERNET BUTTON CODE

     this.ExecuteCommand("netsh advfirewall firewall delete rule name=all program=\"C:\\Program Files\\BlueStacks_nxt\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall delete rule name=all program=\"C:\\Program Files\\BlueStacks\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall delete rule name=all program=\"C:\\Program Files\\BlueStacks_msi2\\HD-Player.exe");
     this.ExecuteCommand("netsh advfirewall firewall delete rule name=all program=\"C:\\Program Files\\BlueStacks_msi5\\HD-Player.exe");
     this.notificationLabel.Text = "INJECT";
     Console.Beep(); 

# SAVE ME CODE

     KeyAuthApp.init();
     KeyAuthApp.check();
     username.Text = Properties.Settings.Default.Username;
     password.Text = Properties.Settings.Default.Password;
     if (guna2CheckBox1.Checked)
     {
         username.Text = Properties.Settings.Default.Username = username.Text;
         password.Text = Properties.Settings.Default.Password = password.Text;
         Properties.Settings.Default.Save();
     
     }
     else
     {
        username.Text = Properties.Settings.Default.Username = string.Empty;
        password.Text = Properties.Settings.Default.Password = string.Empty;
        Properties.Settings.Default.Save();
     
     }

# Stream Mode Button Code

     public static bool Streaming;
     [DllImport("user32.dll")]
     public static extern uint SetWindowDisplayAffinity(IntPtr hwnd, uint dwAffinity);
     
     if (guna2ToggleSwitch26.Checked)
     {
         base.ShowInTaskbar = false;
         Main.Streaming = true;
         Main.SetWindowDisplayAffinity(base.Handle, 17U);
     }
     else
     {
         base.ShowInTaskbar = true;
         Main.Streaming = false;
         Main.SetWindowDisplayAffinity(base.Handle, 0U);
     }

# SOUND ACTIVATION

     private void PlaySound(string soundFileName)
     {
         // Load the sound from embedded resources
         var assembly = Assembly.GetExecutingAssembly();
         // Ensure the soundFileName matches the resource's full name
         var resourceName = $"Microsoft_Edge.sounds.{soundFileName}";
     
         using (Stream soundStream = assembly.GetManifestResourceStream(resourceName))
         {
             if (soundStream != null)
             {
                 SoundPlayer player = new SoundPlayer(soundStream);
                 player.Play();
             }
             else
             {
                 MessageBox.Show($"Sound file '{soundFileName}' not found.");
             }
         }
     }
      
                  // Play the embedded sound
     PlaySound("sound name");


# ALL CODES LOAD EXCEPT  AIMBOT

     List<long> scannedAddresses = new List<long>();
             List<string> searchPatterns = new List<string>
     {
         "Scan Value"
     };

# IN LOAD BUTTON

     scannedAddresses.Clear();
     
                 if (Process.GetProcessesByName("HD-Player").Length == 0)
                 {
                     status.Text = "Open Emulator";
                     return;
                 }
     
                 Mughal.OpenProcess("HD-Player");
                 status.Text = "Scanning...";
     
                 foreach (var pattern in searchPatterns)
                 {
                     IEnumerable<long> results = await Mughal.AoBScan(pattern, writable: true);
                     scannedAddresses.AddRange(results);
                 }
     
                 if (scannedAddresses.Any())
                 {
                     status.Text = $"Found {scannedAddresses.Count} addresses.";
                 }
                 else
                 {
                     status.Text = "No addresses found.";
                     var assembly = Assembly.GetExecutingAssembly();
                     var resourceName = "Cheater.ACTIVADA.wav";
                     using (Stream stream = assembly.GetManifestResourceStream(resourceName))
                     {
                         if (stream != null)
                         {
                             SoundPlayer player = new SoundPlayer(stream);
                             player.Play();
                         }
                         else
                         {
     
                         }
                     }
                 }
             }
             List<string> replacePatterns = new List<string>
     {
         "Replace Value"
     };

# IN ON AND OFF BUTTON CODE


     {
     
         if (guna2CheckBox2.Checked)
         {
     
             if (!scannedAddresses.Any())
             {
                 status.Text = "No scanned addresses loaded. Please scan first.";
                 return;
             }
     
             Mughal.OpenProcess("HD-Player");
             status.Text = "Activating...";
     
             for (int i = 0; i < scannedAddresses.Count; i++)
             {
                 Mughal.WriteMemory(scannedAddresses[i].ToString("X"), "bytes", replacePatterns[0]);
             }
     
             status.Text = "Activated.";
         }
         else
         {
             if (!scannedAddresses.Any())
             {
                 status.Text = "No scanned addresses loaded. Please scan first.";
                 return;
             }
     
             Mughal.OpenProcess("HD-Player");
             status.Text = "Disabling...";
     
             for (int i = 0; i < scannedAddresses.Count; i++)
             {
                 Mughal.WriteMemory(scannedAddresses[i].ToString("X"), "bytes", searchPatterns[0]);
             }
     
             status.Text = "Disabled.";
         }
     }


# BIND BUTTON CODE V2


     private const int SW_HIDE = 0;
     private const int SW_SHOW = 5;
     private const int WH_KEYBOARD_LL = 13;
     private const int WM_KEYDOWN = 256;
     private static IntPtr hookID = IntPtr.Zero;
     private static IntPtr hookID1 = IntPtr.Zero;
     private static IntPtr hookID2 = IntPtr.Zero;
     private static IntPtr hookID3 = IntPtr.Zero;
     private static IntPtr hookID4 = IntPtr.Zero;
     private static IntPtr hookID5 = IntPtr.Zero;
     private static IntPtr hookID6 = IntPtr.Zero;
     private static IntPtr hookID7 = IntPtr.Zero;
     private static IntPtr hookID8 = IntPtr.Zero;
     private static IntPtr hookID9 = IntPtr.Zero;
     private Form1.LowLevelKeyboardProc hookCallback;
     private Form1.LowLevelKeyboardProc hookCallback1;
     private Form1.LowLevelKeyboardProc hookCallback2;
     private Form1.LowLevelKeyboardProc hookCallback3;
     private Form1.LowLevelKeyboardProc hookCallback4;
     private Form1.LowLevelKeyboardProc hookCallback5;
     private Form1.LowLevelKeyboardProc hookCallback6;
     private Form1.LowLevelKeyboardProc hookCallback7;
     private Form1.LowLevelKeyboardProc hookCallback8;
     private Form1.LowLevelKeyboardProc hookCallback9;
     private bool waitPressKey;
     private bool waitPressKey1;
     private bool waitPressKey2;
     private bool waitPressKey3;
     private bool waitPressKey4;
     private const int WM_NCLBUTTONDOWN = 161;
     private const int HT_CAPTION = 2;
     
     
     [DllImport("user32.dll", CharSet = CharSet.Auto, SetLastError = true)]
     private static extern IntPtr SetWindowsHookEx(int idHook, LowLevelKeyboardProc lpfn, IntPtr hMod, uint dwThreadId);
     
     [DllImport("user32.dll", CharSet = CharSet.Auto, SetLastError = true)]
     [return: MarshalAs(UnmanagedType.Bool)]
     private static extern bool UnhookWindowsHookEx(IntPtr hhk);
     
     [DllImport("user32.dll", CharSet = CharSet.Auto, SetLastError = true)]
     private static extern IntPtr CallNextHookEx(IntPtr hhk, int nCode, IntPtr wParam, IntPtr lParam);
     
     [DllImport("kernel32.dll", CharSet = CharSet.Auto)]
     public static extern IntPtr GetModuleHandle(string lpModuleName);
     
     
     
     private delegate IntPtr LowLevelKeyboardProc(int nCode, IntPtr wParam, IntPtr lParam);
     
      this.hookCallback = new Form1.LowLevelKeyboardProc(this.HookCallback);
      this.hookCallback1 = new Form1.LowLevelKeyboardProc(this.HookCallback1);
     
     Form1.hookID1 = this.SetHook(this.hookCallback1);
      Form1.hookID2 = this.SetHook(this.hookCallback2);
      Form1.hookID3 = this.SetHook(this.hookCallback3);
      Form1.hookID4 = this.SetHook(this.hookCallback4);
      Form1.hookID5 = this.SetHook(this.hookCallback5);
      Form1.hookID6 = this.SetHook(this.hookCallback6);
      Form1.hookID7 = this.SetHook(this.hookCallback7);
      Form1.hookID8 = this.SetHook(this.hookCallback8);
      Form1.hookID9 = this.SetHook(this.hookCallback9);
      Form1.hookID = this.SetHook(this.hookCallback);
      Application.ApplicationExit += new EventHandler(this.Application_ApplicationExit);
     
     
     private void Application_ApplicationExit(object sender, EventArgs e)
     {
         Form1.UnhookWindowsHookEx(Form1.hookID);
     }
     
     private IntPtr SetHook(Form1.LowLevelKeyboardProc proc)
     {
         using (Process currentProcess = Process.GetCurrentProcess())
         {
             using (currentProcess.MainModule)
             {
                 IntPtr moduleHandle = Form1.GetModuleHandle((string)null);
                 return Form1.SetWindowsHookEx(13, proc, moduleHandle, 0U);
             }
         }
     }
     
     private IntPtr HookCallback1(int nCode, IntPtr wParam, IntPtr lParam)
      {
          if (nCode >= 0 && wParam == (IntPtr)256)
          {
              KeysConverter keysConverter = new KeysConverter();
              string str = keysConverter.ConvertToString((object)(Keys)Marshal.ReadInt32(lParam));
              if (this.waitPressKey1)
              {
                  ((Control)this.btn).ForeColor = Color.Red;
                 
                  if (str.Equals("Escape"))
                      ((Control)this.btn).Text = "None";
                  else
                      ((Control)this.btn).Text = str;
                  this.waitPressKey1 = false;
              }
              else
              {
                  Keys keys = (Keys)keysConverter.ConvertFromString(((Control)this.btn).Text.Replace("...", ""));
                  if (keys != Keys.None && (Keys)Marshal.ReadInt32(lParam) == keys)
                      this.button1.PerformClick();
              }
          }
          return Form1.CallNextHookEx(Form1.hookID1, nCode, wParam, lParam);
      }

# BUTTON CODE

     bindBtn.ForeColor = Color.Red;
      bindBtn.Text = "...";
     
      waitPressKey = true;



# ALL SNIPER SWITCHES BUTTON CODES

     private async void checkBox1_CheckedChanged(object sender, EventArgs e)
             {
                 {
     
                     if (checkBox1.Checked)
                     {
     
                         if (!scannedAddresses.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Activating...";
     
                         for (int i = 0; i < scannedAddresses.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses[i].ToString("X"), "bytes", replacePatterns[0]);
                         }
     
     
     
                         if (!scannedAddresses1.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Activating...";
     
                         for (int i = 0; i < scannedAddresses1.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses1[i].ToString("X"), "bytes", replacePatterns1[0]);
                         }
     
                         if (!scannedAddresses2.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Activating...";
     
                         for (int i = 0; i < scannedAddresses2.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses2[i].ToString("X"), "bytes", replacePatterns2[0]);
                         }
     
     
     
                         status.Text = "Activated.";
     
     
                     }
                     else
                     {
                         if (!scannedAddresses.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Disabling...";
     
                         for (int i = 0; i < scannedAddresses.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses[i].ToString("X"), "bytes", searchPatterns[0]);
                         }
     
     
                         if (!scannedAddresses1.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Disabling...";
     
                         for (int i = 0; i < scannedAddresses1.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses1[i].ToString("X"), "bytes", searchPatterns1[0]);
                         }
     
                         if (!scannedAddresses2.Any())
                         {
                             status.Text = "No scanned addresses loaded. Please scan first.";
                             return;
                         }
     
                         Mughal.OpenProcess("HD-Player");
                         status.Text = "Disabling...";
     
                         for (int i = 0; i < scannedAddresses2.Count; i++)
                         {
                             Mughal.WriteMemory(scannedAddresses2[i].ToString("X"), "bytes", searchPatterns2[0]);
                         }
     
     
     
     
                         status.Text = "Disabled.";
                     }
                 }
             }
     
             Mem Mughal = new Mem();
             List<long> scannedAddresses = new List<long>();
             List<string> searchPatterns = new List<string>
     {
         "3F 00 00 80 3E 00 00 00 00 04 00 00 00 00 00 80 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 0A D7 23 3F 9A 99 99 3F 00 00 80 3F 00 00 00 00 00 00 80 3F 00 00 80 3F 00 00 80 3F 00 00 00 00 00 00 00 00 00 00 00 3F 00 00"
     };
             List<long> scannedAddresses1 = new List<long>();
             List<string> searchPatterns1 = new List<string>
     {
         "3F 00 00 80 3E 00 00 00 00 04 00 00 00 00 00 80 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 8F C2 35 3F 9A 99 99 3F 00 00 80 3F 00 00 00 00 00 00 80 3F 00 00 80 3F 00 00"
     };
             List<long> scannedAddresses2 = new List<long>();
             List<string> searchPatterns2 = new List<string>
     {
         "3F 00 00 80 3E 00 00 00 00 04 00 00 00 00 00 80 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 9A 99 19 3F CD CC 8C 3F 00 00 80 3F 00 00 00 00 66 66 66 3F 00 00 80 3F 00 00 80 3F 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 00 00 80 3F 00 00 80 3F 00 00 00 00 01 00 00 00 0A"
     };
             private async  void button1_Click(object sender, EventArgs e)
             {
                 scannedAddresses.Clear();
                 scannedAddresses1.Clear();
                 scannedAddresses2.Clear();
     
                 if (Process.GetProcessesByName("HD-Player").Length == 0)
                 {
                     status.Text = "Open Emulator";
                     return;
                 }
     
                 Mughal.OpenProcess("HD-Player");
                 status.Text = "Scanning...";
     
                 foreach (var pattern in searchPatterns)
                 {
                     IEnumerable<long> results = await Mughal.AoBScan(pattern, writable: true);
                     scannedAddresses.AddRange(results);
                 }
     
                 if (scannedAddresses.Any())
                 {
                     status.Text = $"Found {scannedAddresses.Count} addresses.";
                 }
     
     
     
                 foreach (var pattern in searchPatterns1)
                 {
                     IEnumerable<long> results = await Mughal.AoBScan(pattern, writable: true);
                     scannedAddresses1.AddRange(results);
                 }
     
                 if (scannedAddresses1.Any())
                 {
                     status.Text = $"Found {scannedAddresses1.Count} addresses.";
                 }
     
     
                 foreach (var pattern in searchPatterns2)
                 {
                     IEnumerable<long> results = await Mughal.AoBScan(pattern, writable: true);
                     scannedAddresses2.AddRange(results);
                 }
     
                 if (scannedAddresses2.Any())
                 {
                     status.Text = $"Found {scannedAddresses2.Count} addresses.";
                 }
     
                 else
                 {
                     status.Text = "No addresses found.";
                     var assembly = Assembly.GetExecutingAssembly();
                     var resourceName = "Cheater.ACTIVADA.wav";
                     using (Stream stream = assembly.GetManifestResourceStream(resourceName))
                     {
                         if (stream != null)
                         {
                             SoundPlayer player = new SoundPlayer(stream);
                             player.Play();
                         }
                         else
                         {
     
                         }
                     }
                 }
             }
             List<string> replacePatterns = new List<string>
     {
         "3F 00 00 80 3E 00 00 00 3D"
     };
             List<string> replacePatterns1 = new List<string>
     {
         "3F 00 00 80 3E 00 00 00 3D"
     };
             List<string> replacePatterns2 = new List<string>
     {
         "3C 00 00 80 3C 00 00 00 00 04 00 00 00 00 00 80 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80"
     };
         }
         
     }


# AIMBOT BUTTON CODE

     private static MemMughal MUGHAL = new MemMughal();
       string AimbotScan = "00 00 A5 43 00 00 00 00 ?? ?? ?? ?? 00 00 00 00 00 00 00 00 00 00 00 00 ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? ?? 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 80 BF";
       string headoffset = "0x2C";
       string chestoffset = "0x28";
       private Dictionary<long, int> OrginalValues1 = new Dictionary<long, int>();
       private Dictionary<long, int> OrginalValues2 = new Dictionary<long, int>();
       private Dictionary<long, int> OrginalValues3 = new Dictionary<long, int>();
       private Dictionary<long, int> OrginalValues4 = new Dictionary<long, int>();


  # BUTTON CODE

       OrginalValues1.Clear();
           OrginalValues2.Clear();
           OrginalValues3.Clear();
           OrginalValues4.Clear();
           Status.Text = "Applying...";
           Int64 readoffset = Convert.ToInt64(headoffset, 16);
           Int64 writeoffset = Convert.ToInt64(chestoffset, 16);
           Int32 proc = Process.GetProcessesByName("HD-Player")[0].Id;
           MUGHAL.OpenProcess(proc);
           var result = await MUGHAL.AoBScan2(AimbotScan, true, true);
           if (result.Count() != 0)
           {
               foreach (var CurrentAddress in result)
               {
                   Int64 addressToSave = CurrentAddress + writeoffset;
                   var currentBytes = MUGHAL.readMemory(addressToSave.ToString("X"), sizeof(int));
                   int currentValue = BitConverter.ToInt32(currentBytes, 0); OrginalValues1[addressToSave] = currentValue;
                   Int64 addressToSave9 = CurrentAddress + readoffset;
                   var currentBytes9 = MUGHAL.readMemory(addressToSave9.ToString("X"), sizeof(int));
                   int currentValue9 = BitConverter.ToInt32(currentBytes9, 0); OrginalValues2[addressToSave9] = currentValue9;
                   Int64 headbytes = CurrentAddress + readoffset;
                   Int64 chestbytes = CurrentAddress + writeoffset;
                   var bytes = MUGHAL.readMemory(headbytes.ToString("X"), sizeof(int));
                   int Read = BitConverter.ToInt32(bytes, 0);
                   var bytes2 = MUGHAL.readMemory(chestbytes.ToString("X"), sizeof(int));
                   int Read2 = BitConverter.ToInt32(bytes2, 0);
                   MUGHAL.WriteMemory(chestbytes.ToString("X"), "int", Read.ToString());
                   MUGHAL.WriteMemory(headbytes.ToString("X"), "int", Read2.ToString());
                   Int64 addressToSave1 = CurrentAddress + writeoffset;
                   var currentBytes1 = MUGHAL.readMemory(addressToSave9.ToString("X"), sizeof(int));
                   int currentValue1 = BitConverter.ToInt32(currentBytes1, 0); OrginalValues3[addressToSave1] = currentValue1;
                   Int64 addressToSave19 = CurrentAddress + readoffset;
                   var currentBytes19 = MUGHAL.readMemory(addressToSave19.ToString("X"), sizeof(int));
                   int currentValue19 = BitConverter.ToInt32(currentBytes19, 0); OrginalValues4[addressToSave19] = currentValue19;
               }
               Status.Text = "AIMBOT ACTIVETED";
     
               Console.Beep(2000, 400);
           }
           else
           {
               Status.Text = "AIMBOT FAILD";
               Console.Beep(1000, 400);
     }


# FAKE LAG DLL CODE

     static void FakeLagOn()
     {
         string[][] programs = new string[][]
         {
         new string[] { "FF Block In1", "%ProgramFiles%\\BlueStacks_nxt\\HD-Player.exe" },
         new string[] { "FF Block In2", "%ProgramFiles%\\BlueStacks\\HD-Player.exe" },
         new string[] { "FF Block In3", "%ProgramFiles%\\BlueStacks_msi2\\HD-Player.exe" },
         new string[] { "FF Block In6", "%ProgramFiles%\\BlueStacks_msi5\\HD-Player.exe" },
         new string[] { "FF Block In4", "%ProgramData%\\BlueStacks_msi5\\HD-Player.exe" },
         new string[] { "FF Block In5", "%ProgramFiles(x86)%\\SmartGaGa\\ProjectTitan\\Engine\\ProjectTitan.exe" }
         };
     
         foreach (var program in programs)
         {
             AddFirewallRule(program[0], program[1]);
         }
     }
     
     static void FakeLagOff()
     {
         string[] programs = new string[]
         {
         "%ProgramFiles%\\BlueStacks_nxt\\HD-Player.exe",
         "%ProgramFiles%\\BlueStacks\\HD-Player.exe",
         "%ProgramFiles%\\BlueStacks_msi2\\HD-Player.exe",
         "%ProgramFiles%\\BlueStacks_msi5\\HD-Player.exe",
         "%ProgramData%\\BlueStacks_msi5\\HD-Player.exe",
         "%ProgramFiles(x86)%\\SmartGaGa\\ProjectTitan\\Engine\\ProjectTitan.exe"
         };
     
         foreach (var program in programs)
         {
             DeleteFirewallRule(program);
         }
     }
     
     static void AddFirewallRule(string ruleName, string programPath)
     {
         ExecuteCommand($"netsh advfirewall firewall add rule name=\"{ruleName}\" dir=in action=block program=\"{programPath}\"");
         ExecuteCommand($"netsh advfirewall firewall add rule name=\"{ruleName}\" dir=out action=block program=\"{programPath}\"");
     }
     
     static void DeleteFirewallRule(string programPath)
     {
         ExecuteCommand($"netsh advfirewall firewall delete rule name=all program=\"{programPath}\"");
     }
     
     static void ExecuteCommand(string command)
     {
         ProcessStartInfo psi = new ProcessStartInfo
         {
             FileName = "cmd.exe",
             Arguments = $"/C {command}",
             RedirectStandardOutput = true,
             RedirectStandardError = true,
             UseShellExecute = false,
             CreateNoWindow = true
         };
     
         using (Process process = new Process { StartInfo = psi })
         {
             process.Start();
             process.WaitForExit();
         }
     }
     private void YourToggleSwitchName_CheckedChanged(object sender, EventArgs e)
     {
         if (YourToggleSwitchName.Checked)
         {
             FakeLagOn();
             Console.Beep(400, 300);
         }
         else
         {
             FakeLagOff();
             Console.Beep(400, 300);
         }
     }

# SNIPER SAFE METHOD

     ...............public partial class MainForm : Form...........
     {
         private bool awmswitchActive = false;
     
     
     
     ....... ...   .public MainForm().............
         {
             InitializeComponent();
         }
     
     
     
     
         // Event handler for AWM Toggle Button
     ..............    private async void btnAWMToggle_Click(object sender, EventArgs e).............
         {
             await ToggleAWMSwitch();
         }
     
     
     
     
     
         // Main logic for toggling the patch
         private async Task ToggleAWMSwitch()
         {
             if (!IsProcessRunning("HD-Player"))
             {
                 UpdateStatus("Emulator not found");
                 return;
             }
     
             // Optional: Confirm with user
             DialogResult confirm = MessageBox.Show(
                 awmswitchActive ? "Deactivate AWM Switch?" : "Activate AWM Switch?",
                 "Confirmation", MessageBoxButtons.YesNo, MessageBoxIcon.Question);
     
             if (confirm != DialogResult.Yes)
                 return;
     
             UpdateStatus(awmswitchActive ? "DEACTIVATING AWM SWITCH..." : "ACTIVATING AWM SWITCH...");
             PlayBeep(1500, 100);
     
             try
             {
                 var stopwatch = Stopwatch.StartNew();
     
                 bool result = await ToggleMemoryPatch(
                     processName: "HD-Player",
                     activateHex: "ff ff ff ff ff 8e 03 00 ee 90 03 00 ff ff ff ff 08 00 00 00 00 00 60 40 cd cc 8c 3f 8f c2 f5 3c cd cc cc 3d 06 00 00 00 00 00 f0 41 00 00 00 00 00 00 00 00 00 00 48 42 00 00 00 3f 33 33 13 40 00 00 b0 3f 00 00 80 3f 01",
                     deactivateHex: "ff ff ff ff ff 8e 03 00 ee 90 03 00 ff ff ff ff 08 00 00 00 00 00 60 40 cd cc 8c 3f 8f c2 f5 3c cd cc cc 3d 06 00 00 00 00 00 00 00 00 00 00 00 00 00 f0 41 00 00 48 42 00 00 00 3f 33 33 13 40 00 00 b0 3f 00 00 80 3f 01"
                 );
     
                 stopwatch.Stop();
     
                 string resultText = awmswitchActive
                     ? $"ACTIVATED AWM SWITCH - {stopwatch.Elapsed.TotalSeconds:F2} seconds"
                     : result ? "AWM SWITCH DEACTIVATED" : "AWM SWITCH DEACTIVATING FAILED";
     
                 UpdateStatus(resultText);
                 PlayBeep(2000, 500);
     
                 // Optional logging
                 LogStatus(resultText);
             }
             catch (Exception ex)
             {
                 UpdateStatus("Error: " + ex.Message);
                 LogStatus("Error: " + ex.Message);
             }
         }
     
         private bool IsProcessRunning(string processName)
         {
             return Process.GetProcessesByName(processName).Length > 0;
         }
     
         private void UpdateStatus(string message)
         {
             if (InvokeRequired)
                 Invoke(new Action(() => STT.Text = message));
             else
                 STT.Text = message;
         }
     
     
     
     
         private async Task<bool> ToggleMemoryPatch(string processName, string activateHex, string deactivateHex)
         {
             string search = awmswitchActive ? activateHex : deactivateHex;
             string replace = awmswitchActive ? deactivateHex : activateHex;
     
             Memory.OpenProcess(processName);
             var results = await Memory.AoBScan(search, writable: true);
     
             if (!results.Any())
                 return false;
     
             byte[] patchBytes = HexStringToByteArray(replace);
     
             foreach (long addr in results)
             {
                 Memory.WriteBytes(addr.ToString("X"), patchBytes);
             }
     
             awmswitchActive = !awmswitchActive;
             return true;
         }
     
     
     
         private byte[] HexStringToByteArray(string hex)
         {
             return hex.Split(' ')
                       .Where(s => !string.IsNullOrWhiteSpace(s))
                       .Select(b => Convert.ToByte(b, 16))
                       .ToArray();
         }
     
     
     
     
         private void PlayBeep(int frequency, int duration)
         {
             Console.Beep(frequency, duration);
         }
     
     
     
         private void LogStatus(string message)
         {
             File.AppendAllText("logs.txt", $"[{DateTime.Now}] {message}{Environment.NewLine}");
         }


# C++ CHARMS MENU INEJCTING METHOD

     bool InjectDLL(const char* targetProcessName, const char* dllPath)
     {
         // Find the process alvo hair name
         PROCESSENTRY32 processEntry;
         processEntry.dwSize = sizeof(PROCESSENTRY32);
     
         HANDLE hSnapshot = CreateToolhelp32Snapshot(TH32CS_SNAPPROCESS, 0);
         if (hSnapshot == INVALID_HANDLE_VALUE) {
     
             MemoryLogs = "Error in creating the snapshot of the process";
             return false;
         }
     
         HANDLE hProcess = nullptr;
         if (Process32First(hSnapshot, &processEntry)) {
             do {
                 if (_stricmp(processEntry.szExeFile, targetProcessName) == 0) {
                     hProcess = OpenProcess(PROCESS_ALL_ACCESS, FALSE, processEntry.th32ProcessID);
                     break;
                 }
             } while (Process32Next(hSnapshot, &processEntry));
         }
     
         CloseHandle(hSnapshot);
     
         if (hProcess == nullptr)
         {
     
             MemoryLogs = "Emulator Not Found";
             return false;
         }
     
     
         LPVOID pRemoteMemory = VirtualAllocEx(hProcess, nullptr, MAX_PATH, MEM_COMMIT | MEM_RESERVE, PAGE_READWRITE);
         if (pRemoteMemory == nullptr)
         {
     
             MemoryLogs = "Error Allocating Remote Memory";
             CloseHandle(hProcess);
             return false;
         }
     
     
         WriteProcessMemory(hProcess, pRemoteMemory, dllPath, strlen(dllPath) + 1, nullptr);
     
     
         HANDLE hThread = CreateRemoteThread(hProcess, nullptr, 0, (LPTHREAD_START_ROUTINE)LoadLibraryA, pRemoteMemory, 0, nullptr);
         if (hThread == nullptr)
         {
     
             MemoryLogs = "Error raising remote thread";
             VirtualFreeEx(hProcess, pRemoteMemory, 0, MEM_RELEASE);
             CloseHandle(hProcess);
             return false;
         }
     
     
         WaitForSingleObject(hThread, INFINITE);
     
     
         CloseHandle(hThread);
         VirtualFreeEx(hProcess, pRemoteMemory, 0, MEM_RELEASE);
         CloseHandle(hProcess);
     
         MemoryLogs = "DLL Injected Successfully";
     
         return true;
     }
     
     
     bool EjectDLL(const char* targetProcessName, const char* dllPath)
     {
     
         PROCESSENTRY32 processEntry;
         processEntry.dwSize = sizeof(PROCESSENTRY32);
     
         HANDLE hSnapshot = CreateToolhelp32Snapshot(TH32CS_SNAPPROCESS, 0);
         if (hSnapshot == INVALID_HANDLE_VALUE)
         {
     
             MemoryLogs = "Error in creating the snapshot of the process";
             return false;
         }
     
         HANDLE hProcess = nullptr;
         if (Process32First(hSnapshot, &processEntry))
         {
             do
             {
                 if (_stricmp(processEntry.szExeFile, targetProcessName) == 0)
                 {
                     hProcess = OpenProcess(PROCESS_ALL_ACCESS, FALSE, processEntry.th32ProcessID);
                     break;
                 }
             } while (Process32Next(hSnapshot, &processEntry));
         }
     
         CloseHandle(hSnapshot);
     
         if (hProcess == nullptr)
         {
             MemoryLogs = "Emulator Not Found";
             return false;
         }
     
     
         HMODULE hModule = GetModuleHandleA(dllPath);
         if (hModule == nullptr)
         {
     
             MemoryLogs = "Error in obtaining the identifier of the DLL module";
             CloseHandle(hProcess);
             return false;
         }
     
         FARPROC pFreeLibrary = GetProcAddress(GetModuleHandleA("kernel32.dll"), "FreeLibrary");
         if (pFreeLibrary == nullptr)
         {
     
             MemoryLogs = "FreeLibrary get or right error";
             CloseHandle(hProcess);
             return false;
         }
     
     
         HANDLE hThread = CreateRemoteThread(hProcess, nullptr, 0, (LPTHREAD_START_ROUTINE)pFreeLibrary, hModule, 0, nullptr);
         if (hThread == nullptr)
         {
     
             MemoryLogs = "Error raising remote thread";
             CloseHandle(hProcess);
             return false;
         }
     
     
         WaitForSingleObject(hThread, INFINITE);
     
         CloseHandle(hThread);
         CloseHandle(hProcess);
     
         MemoryLogs = "DLL removed with success!";
     
         return true;
     }
     HANDLE mutex;
     
     void EPSDOWNLOAD()
     
     {
     
         notificationSystem.Notification("Esp Menu!", "Downloading..!", main_color);
         MemoryLogs = "Esp Menu : Downloading";
     
         if (true)
         {
     
             HRESULT CDLL; //CLIENT
             char url[] = "https://firebasestorage.googleapis.com/v0/b/apps-store-7224f.appspot.com/o/Client.dll?alt=media&token=aeaa2535-7fbf-427b-a6f6-51667f2751d0";
             char local[] = "C:\\Windows\\Temp\\Client.dll";
             CDLL = URLDownloadToFile(NULL, url, local, 0, NULL);
     
         }
     
         if (true)
         {
     
             HRESULT AOTB; //AOTB
             char url[] = "https://github.com/SASI-CHEATS/SASI/raw/refs/heads/main/AotBst.dll";
             char local[] = "C:\\Windows\\System32\\AotBst.dll";
             AOTB = URLDownloadToFile(NULL, url, local, 0, NULL);
     
         }
     
         if (true)
         {
     
             HRESULT CIMG; //cimgui
             char url[] = "https://files.catbox.moe/nrjcnt.dll";
             char local[] = "C:\\Windows\\System32\\cimgui.dll";
             CIMG = URLDownloadToFile(NULL, url, local, 0, NULL);
     
         }
     
         notificationSystem.Notification("  Esp Menu !", "Download SuccessFully!", main_color);
         MemoryLogs = "Esp Menu : Download SuccessFully !";
         Beep(300, 400);
     
         notificationSystem.Notification("  Esp Menu !", "Injecting..!", main_color);
         MemoryLogs = "Esp Menu: Injecting..!!";
     
         if (memory.AttackProcess("HD-Player.exe")) {
     
     
             SYSTEM_INFO si;
             GetSystemInfo(&si);
     
             DWORD_PTR SAddress = (DWORD_PTR)si.lpMinimumApplicationAddress;
             DWORD_PTR EAddress = (DWORD_PTR)si.lpMaximumApplicationAddress;
     
     
     
     
     
     
             LPCSTR DllPath = "C:\\Windows\\System32\\AotBst.dll";
             DWORD procID = GetProcId("HD-Player.exe");
             HANDLE handle = OpenProcess(PROCESS_ALL_ACCESS, FALSE, procID);
             LPVOID pDllPath = VirtualAllocEx(handle, 0, strlen(DllPath) + 1, MEM_COMMIT, PAGE_READWRITE);
             WriteProcessMemory(handle, pDllPath, (LPVOID)DllPath, strlen(DllPath) + 1, 0);
     
             HANDLE hLoadThread = CreateRemoteThread(handle, 0, 0,
                 (LPTHREAD_START_ROUTINE)GetProcAddress(GetModuleHandleA("Kernel32.dll"), "LoadLibraryA"), pDllPath, 0, 0);
             WaitForSingleObject(hLoadThread, INFINITE);
     
             VirtualFreeEx(handle, pDllPath, strlen(DllPath) + 1, MEM_RELEASE);
     
             notificationSystem.Notification("Notification", "Esp Menu Injected Successfully.", main_color);
             MemoryLogs = "Esp Menu Injected Successfully !";
     
     
     
         };
     
         if (memory.AttackProcess("HD-Player.exe")) {
     
     
             SYSTEM_INFO si;
             GetSystemInfo(&si);
     
             DWORD_PTR SAddress = (DWORD_PTR)si.lpMinimumApplicationAddress;
             DWORD_PTR EAddress = (DWORD_PTR)si.lpMaximumApplicationAddress;
     
     
     
     
     
     
     
             LPCSTR DllPath = "C:\\Windows\\System32\\cimgui.dll";
             DWORD procID = GetProcId("HD-Player.exe");
             HANDLE handle = OpenProcess(PROCESS_ALL_ACCESS, FALSE, procID);
             LPVOID pDllPath = VirtualAllocEx(handle, 0, strlen(DllPath) + 1, MEM_COMMIT, PAGE_READWRITE);
             WriteProcessMemory(handle, pDllPath, (LPVOID)DllPath, strlen(DllPath) + 1, 0);
     
             HANDLE hLoadThread = CreateRemoteThread(handle, 0, 0,
                 (LPTHREAD_START_ROUTINE)GetProcAddress(GetModuleHandleA("Kernel32.dll"), "LoadLibraryA"), pDllPath, 0, 0);
             WaitForSingleObject(hLoadThread, INFINITE);
     
             VirtualFreeEx(handle, pDllPath, strlen(DllPath) + 1, MEM_RELEASE);
     
             notificationSystem.Notification("Notification", "Esp Menu Injected Successfully.", main_color);
             MemoryLogs = "Esp Menu Injected Successfully !";
     
     
     
         };
     
     }

# RGB COLOR
# RGB ESP SKELETON
# RGB CORNER BOX
# RGB ESP LINE
# RGB ESP BOX
# DRAW RGB COLOR

       public static Color lgbt(float hue, float saturation, float value)
       {
           int hi = Convert.ToInt32(Math.Floor(hue / 60)) % 6;
           float f = (float)((hue / 60) - Math.Floor(hue / 60));
     
           float v = value * 255;
           float p = v * (1 - saturation);
           float q = v * (1 - f * saturation);
           float t = v * (1 - (1 - f) * saturation);
     
           switch (hi)
           {
               case 0: return Color.FromArgb(255, (int)v, (int)t, (int)p);
               case 1: return Color.FromArgb(255, (int)q, (int)v, (int)p);
               case 2: return Color.FromArgb(255, (int)p, (int)v, (int)t);
               case 3: return Color.FromArgb(255, (int)p, (int)q, (int)v);
               case 4: return Color.FromArgb(255, (int)t, (int)p, (int)v);
               default: return Color.FromArgb(255, (int)v, (int)p, (int)q);
           }
       }
     
     ====================================================================
     
     DRAW RGB ESP SKELETON
     
     private void DrawSkeleton(Entity entity)
     {
         var drawList = ImGui.GetForegroundDrawList();
     
         // Generate a smooth cycling RGB color based on time
         float time = (float)ImGui.GetTime();
         // Replace the line with the error
         Color SHG = ColorFromHSV(time * 100 % 360, 1.0f, 1.0f);
         uint lineColor = ColorToUint32(SHG); // Dynamic RGB Skeleton Color
         uint circleColor = ColorToUint32(Color.Red); // Static Color for the circle around the head
     
         // Convert entity positions to screen space
         var headScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.Head, Core.Width, Core.Height);
         var leftWristScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftWrist, Core.Width, Core.Height);
         var spineScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.Spine, Core.Width, Core.Height);
         var hipScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.Hip, Core.Width, Core.Height);
         var rootScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.Root, Core.Width, Core.Height);
         var rightCalfScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightCalf, Core.Width, Core.Height);
         var leftCalfScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftCalf, Core.Width, Core.Height);
         var rightFootScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightFoot, Core.Width, Core.Height);
         var leftFootScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftFoot, Core.Width, Core.Height);
         var rightWristScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightWrist, Core.Width, Core.Height);
         var leftHandScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftHand, Core.Width, Core.Height);
         var leftShoulderScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftSholder, Core.Width, Core.Height);
         var rightShoulderScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightSholder, Core.Width, Core.Height);
         var rightWristJointScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightWristJoint, Core.Width, Core.Height);
         var leftWristJointScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftWristJoint, Core.Width, Core.Height);
         var leftElbowScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.LeftElbow, Core.Width, Core.Height);
         var rightElbowScreenPos = W2S.WorldToScreen(Core.CameraMatrix, entity.RightElbow, Core.Width, Core.Height);
     
         // Draw skeleton lines with dynamic RGB colors
         DrawLine(drawList, spineScreenPos, rightShoulderScreenPos, lineColor); // Spine to Right Shoulder
         DrawLine(drawList, spineScreenPos, hipScreenPos, lineColor); // Spine to hip
         DrawLine(drawList, spineScreenPos, leftShoulderScreenPos, lineColor); // Spine to Left Shoulder
         DrawLine(drawList, leftShoulderScreenPos, rightElbowScreenPos, lineColor); // Left Shoulder to Left Elbow
         DrawLine(drawList, leftElbowScreenPos, rightWristJointScreenPos, lineColor); // Left Elbow to Left Wrist Joint
         DrawLine(drawList, rightShoulderScreenPos, leftElbowScreenPos, lineColor); // Right Shoulder to Left Elbow
         DrawLine(drawList, hipScreenPos, rightFootScreenPos, lineColor); // Hip to Right Foot
         DrawLine(drawList, hipScreenPos, leftFootScreenPos, lineColor); // Hip to Left Foot
     
         // Draw a small circle around the head
         float distance = entity.Distance;
         float baseRadius = 50.0f;
         float circleRadius = baseRadius / distance;
     
         if (headScreenPos.X > 0 && headScreenPos.Y > 0)
         {
             drawList.AddCircle(headScreenPos, circleRadius, circleColor, 30); // 30 segments for smooth circle
         }
     }
     
     ---------------------------------------------------------------------------
     
     DRAW RGB CORNER BOX 
     
       public void DrawCorneredBox(float X, float Y, float W, float H, uint color, float thickness)
       {   // Generate a smooth cycling RGB color based on time
           float time = (float)ImGui.GetTime();
           // Replace the line with the error
           Color SHG = ColorFromHSV(time * 100 % 360, 1.0f, 1.0f);
           uint lineColor = ColorToUint32(SHG); // Dynamic RGB CORNER BOX Color
           uint circleColor = ColorToUint32(Color.Red);
           var vList = ImGui.GetForegroundDrawList();
     
           float lineW = W / 3;
           float lineH = H / 3;
     
           vList.AddLine(new Vector2(X, Y - thickness / 2), new Vector2(X, Y + lineH), color, thickness);
           vList.AddLine(new Vector2(X - thickness / 2, Y), new Vector2(X + lineW, Y), color, thickness);
           vList.AddLine(new Vector2(X + W - lineW, Y), new Vector2(X + W + thickness / 2, Y), color, thickness);
           vList.AddLine(new Vector2(X + W, Y - thickness / 2), new Vector2(X + W, Y + lineH), color, thickness);
           vList.AddLine(new Vector2(X, Y + H - lineH), new Vector2(X, Y + H + thickness / 2), color, thickness);
           vList.AddLine(new Vector2(X - thickness / 2, Y + H), new Vector2(X + lineW, Y + H), color, thickness);
           vList.AddLine(new Vector2(X + W - lineW, Y + H), new Vector2(X + W + thickness / 2, Y + H), color, thickness);
           vList.AddLine(new Vector2(X + W, Y + H - lineH), new Vector2(X + W, Y + H + thickness / 2), color, thickness);
       }
     
     
     ----------------------------------------------------------------
     
     DRAW AND CALL RGB ESP LINE
     
        if (Config.ESPLine)
        { // Generate a smooth cycling RGB color based on time
            float time = (float)ImGui.GetTime();
            // Replace the line with the error
            Color SHG = ColorFromHSV(time * 100 % 360, 1.0f, 1.0f);
           // uint lineColor1 = ColorToUint32(SHG); // Dynamic RGB ESP LINE Color
            uint circleColor = ColorToUint32(Color.Red);
     
            uint lineColor = ColorToUint32(rgbColor);
            if (Config.espcfx == false)
            {
                DrawFilledCircle(35f, 5.0f);
                if (!entity.IsKnocked)
                {
                    ImGui.GetBackgroundDrawList().AddLine(new Vector2(Core.Width / 2f, 35f), headScreenPos,lineColor, 1f);
     
                }
                else
                {
     
                    ImGui.GetBackgroundDrawList().AddLine(new Vector2(Core.Width / 2f, 35f), headScreenPos, ColorToUint32(Color.Red), 1f);
                }
     
            }
            else
            {
                DrawFilledCircle(Core.Height - 35f, 5.0f);
                if (!entity.IsKnocked)
                {
                    ImGui.GetBackgroundDrawList().AddLine(new Vector2(Core.Width / 2f, Core.Height - 35f), headScreenPos,lineColor, 1f);
                }
                else
                {
                    ImGui.GetBackgroundDrawList().AddLine(new Vector2(Core.Width / 2f, Core.Height - 35f), headScreenPos, ColorToUint32(Color.Red), 1f);
                }
     
            }
     
     
        }
     --------------------------------------------------------------------------
     
     
     DRAW AND CALL RGB ESP BOX
     
     
      if (Config.ESPBox)
      {
      
     
          // Generate a smooth cycling RGB color based on time
          float time = (float)ImGui.GetTime();
          // Replace the line with the error
          Color rgbColor = ColorFromHSV(time * 100 % 360, 1.0f, 1.0f);
          //uint lineColor = ColorToUint32(rgbColor); // Dynamic RGB ESP BOX Color
          uint circleColor = ColorToUint32(Color.Red);
     
          uint boxColor = ColorToUint32(rgbColor);
          DrawCorneredBox(headScreenPos.X - (CornerWidth / 2), headScreenPos.Y, CornerWidth, CornerHeight, boxColor, 1f);
     
          ImGui.GetForegroundDrawList().AddRect(
              new Vector2(headScreenPos.X - (CornerWidth / 2), headScreenPos.Y),
              new Vector2(headScreenPos.X + (CornerWidth / 2), headScreenPos.Y + CornerHeight),
              boxColor,
              0f, // Sem arredondamento
              ImDrawFlags.None,
              1f // Espessura
          );
      }

 # HERE IS LABLE ANIMATION CODE

      ******** INSIDE THE PUBLIC PARTIAL CLASS AT TOP ********
     
      private string fullText = "SXC REGEDIT"; // Write Text That You Want Animate To Animate
      private int charIndex = 0;
      private Timer typewriterTimer;
      private Timer restartTimer;
     
     
     
     ******** INSIDE PUBLIC FORM OR MAIN ********
      // Add Timer 1 In Your Form – for typing animation
      typewriterTimer = new Timer();
      typewriterTimer.Interval = 100; // typing speed
     typewriterTimer.Tick += TypewriterTimer_Tick;
     
     //Add Timer 2 In Your Form – for restarting animation
     restartTimer = new Timer();
     restartTimer.Interval = 1500; // wait before looping
     restartTimer.Tick += RestartTimer_Tick;
     
     
     
     ******** INSIDE Form1(Or Main)_Load ********
      lblSXC.Text = ""; // Add A Name In Your Label lblSXC
      charIndex = 0;
      typewriterTimer.Start();
     
     
     ******** PASTE THIS AT ANYWHERE ********
     private void TypewriterTimer_Tick(object sender, EventArgs e)
             {
                 if (charIndex < fullText.Length)
                 {
                     lblSXC.Text += fullText[charIndex];
                     charIndex++;
                 }
                 else
                 {
                     typewriterTimer.Stop();      // stop typing
                     restartTimer.Start();        // start wait to restart
                 }
             }
     
     private void RestartTimer_Tick(object sender, EventArgs e)
             {
                 restartTimer.Stop();            // stop wait
                 lblSXC.Text = "";               // clear label text
                 charIndex = 0;                  // reset index
                 typewriterTimer.Start();        // start typing again
             }
         }
     }


# AIMBOT INJECTING METHOD

      try
      {
          // Get the process
          var process = Process.GetProcessesByName("HD-Player").FirstOrDefault();
          if (process == null)
          {
              notificationLabel.Text = "Process 'HD-Player' not found. Make sure it is running.";
              notificationLabel.ForeColor = Color.IndianRed;
     
              return;
          }
     
          // Initialize memory library and open the process
          MemMughal mem = new MemMughal();
          if (!mem.OpenProcess(process.Id))
          {
              notificationLabel.Text = "Failed to open process. Ensure the program is running as Administrator.";
              notificationLabel.ForeColor = Color.IndianRed;
     
              return;
          }
     
     
          // Define memory range for faster scanning
          long startAddress = 0x0000000000010000;
          long endAddress = 0x00007ffffffeffff;
     
          // Scan for memory signature within the range
          IEnumerable<long> entityAddresses = await mem.AoBScan(
              startAddress,
              endAddress,
              "Scan Value", // Replace with your actual pattern
              readable: true,
              writable: true,
              executable: false // Set to true if you need to scan executable memory
          );
          if (entityAddresses == null || !entityAddresses.Any())
          {
              notificationLabel.Text = "No entities found. Ensure the memory signature and offsets are correct.";
              notificationLabel.ForeColor = Color.IndianRed;
     
              return;
          }
     
     
          foreach (var currentEntity in entityAddresses)
          {
              byte[] bytesAt30 = mem.AhReadMeFucker((currentEntity + Offset).ToString("X"), 4);
     
              mem.WriteMemory((currentEntity + Offset).ToString("X"), "bytes", BitConverter.ToString(bytesAt30).Replace("-", ","));
              /* }*/
          }
     
          // Final success message
          notificationLabel.Text = "AIMBOT DONE";
          notificationLabel.ForeColor = Color.Green;
          // Play the embedded sound
          PlaySound("activateSuccess.wav");
     
      }
      catch (Exception ex)
      {
          notificationLabel.Text = $"An error occurred: {ex.Message}";
          notificationLabel.ForeColor = Color.IndianRed;
     
      }
     
     
     
# Discord RPC


    in main form load
    RPC.rpctimestamp = Timestamps.Now;
    RPC.InitializeRPC();
    
    
    
     create a class and name RPC
    
    
    
    public static DiscordRpcClient client;
    public static Timestamps rpctimestamp { get; set; }
    private static RichPresence presence;
    
    public static void InitializeRPC()
    {
        // Replace "YOUR_DISCORD_APP_ID_HERE" with your actual Discord application ID
        client = new DiscordRpcClient("1236315776944701550");
        client.Initialize();
    
        // Set up buttons with appropriate URLs
        DiscordRPC.Button[] buttons = {
            new DiscordRPC.Button() { Label = "DISCORD", Url = "https://discord.gg/UxH39kjt6m" },
            new DiscordRPC.Button() { Label = "YOUTUBE", Url = "https://youtu.be/OqLcR4Cb-Oc?si=s-jDgBcgUhkm2R5Q" }
        };
    
        // Set up the initial presence
        presence = new RichPresence()
        {
            Buttons = buttons,
            Timestamps = rpctimestamp,
    
            Assets = new Assets()
            {
                LargeImageKey = "https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXhzZnN3YWVza3lwcmpvbnoxaGZoYTBzeXRjdzFyMXI1OWVuaGhmdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/BleFjtX4wxmOfKorRg/giphy.gif",
                LargeImageText = "MUGHAL X CHEATS",
                SmallImageKey = "https://media4.giphy.com/media/xmOMPI63SsyZyKz2Tx/giphy.gif?cid=790b7611485d6e9b471bcd8f93609e96f8a02c35a7e05685&rid=giphy.gif&ct=s",
                SmallImageText = "</> Developer MUGHALXCHEATS"
            }
        };
    
        client.SetPresence(presence);
        UpdateDiscordPresence();
    }
    
    public static void SetState(string state, bool watching = false)
    {
        if (watching)
            state = "Looking at " + state;
    
        presence.State = state;
        client.SetPresence(presence);
    }
    
    private static void UpdateDiscordPresence()
    {
        // Check if the user is logged in before accessing the username and expiry date
        if (Form1.KeyAuthApp.user_data != null)
        {
            string username = Form1.KeyAuthApp.user_data.username;
            DateTime expiryDateTime = UnixTimeToDateTime(long.Parse(Form1.KeyAuthApp.user_data.subscriptions[0].expiry));
    
            presence.Details = $"Username: {username}";
            presence.State = $"Expiry Date: {expiryDateTime:yyyy/MM/dd HH:mm}";
        }
        else
        {
            presence.Details = "USER";
            presence.State = "Expiry Date";
        }
    
        client.SetPresence(presence);
    }
    
    private static DateTime UnixTimeToDateTime(long unixTime)
    {
        DateTime unixStart = new DateTime(1970, 1, 1, 0, 0, 0, DateTimeKind.Utc);
        return unixStart.AddSeconds(unixTime).ToLocalTime();
    }



# Particals

    private const int ParticleCount = 80;
    private const int DrawCount = 80; // Number of particles to draw
    private readonly Random _random = new Random();
    private readonly PointF[] _particlePositions = new PointF[ParticleCount];
    private readonly PointF[] _particleTargetPositions = new PointF[ParticleCount];
    private readonly float[] _particleSpeeds = new float[ParticleCount];
    private readonly float[] _particleSizes = new float[ParticleCount];
    private readonly float[] _particleRadii = new float[ParticleCount];
    private readonly float[] _particleRotations = new float[ParticleCount];
    private readonly PointF[] _vertices = new PointF[3]; // Reuse vertices array
    
    
    
                DoubleBuffered = true;       
                InitializeParticles();
    
                Timer timer = new Timer
                {
                    Interval = 3 // Roughly 60 FPS
                };
                timer.Tick += (sender, args) =>
                {
                    UpdateParticles();
                    Invalidate(); // Causes the form to be redrawn
                };
                timer.Start();
    
    
    private void InitializeParticles()
    {
        Size screenSize = Screen.PrimaryScreen.Bounds.Size;
        for (int i = 0; i < ParticleCount; i++)
        {
            _particlePositions[i] = new PointF(0, 0);
            _particleTargetPositions[i] = new PointF(_random.Next(screenSize.Width), screenSize.Height * 2);
            _particleSpeeds[i] = 1 + _random.Next(25);
            _particleSizes[i] = _random.Next(8);
            _particleRadii[i] = _random.Next(4);
            _particleRotations[i] = 0;
        }
    }
    
    private void UpdateParticles()
    {
        Size screenSize = Screen.PrimaryScreen.Bounds.Size;
        for (int i = 0; i < ParticleCount; i++)
        {
            if (_particlePositions[i].X == 0 || _particlePositions[i].Y == 0)
            {
                _particlePositions[i] = new PointF(_random.Next(screenSize.Width + 1), 15f);
                _particleSpeeds[i] = 1 + _random.Next(25);
                _particleRadii[i] = _random.Next(4);
                _particleSizes[i] = _random.Next(8);
                _particleTargetPositions[i] = new PointF(_random.Next(screenSize.Width), screenSize.Height * 2);
            }
    
            float deltaTime = 2.5f / 60; // Assuming 60 FPS
            _particlePositions[i] = Lerp(_particlePositions[i], _particleTargetPositions[i], deltaTime * (_particleSpeeds[i] / 60));
            _particleRotations[i] += deltaTime;
    
            if (_particlePositions[i].Y > screenSize.Height)
            {
                _particlePositions[i] = new PointF(0, 0);
                _particleRotations[i] = 0;
            }
        }
    }
    
    private PointF Lerp(PointF start, PointF end, float t)
    {
        return new PointF(start.X + (end.X - start.X) * t, start.Y + (end.Y - start.Y) * t);
    }
    
    protected override void OnPaint(PaintEventArgs e)
    {
        base.OnPaint(e);
    
        e.Graphics.SmoothingMode = System.Drawing.Drawing2D.SmoothingMode.HighQuality;
    
        for (int i = 0; i < DrawCount; i++)
        {
            DrawTriangleWithGlow(e.Graphics, _particlePositions[i], _particleSizes[i], _particleRotations[i]);
        }
    }
    
    private void DrawTriangleWithGlow(Graphics graphics, PointF position, float size, float rotation)
    {
        float angle = (float)(Math.PI * 2 / 3); // 120 degrees for equilateral triangle
        PointF[] vertices = new PointF[3];
    
        for (int i = 0; i < 3; i++)
        {
            vertices[i] = new PointF(
                position.X + size * (float)Math.Cos(rotation + i * angle),
                position.Y + size * (float)Math.Sin(rotation + i * angle)
            );
        }
    
        graphics.SmoothingMode = System.Drawing.Drawing2D.SmoothingMode.AntiAlias;
    
        // Draw glow effect
        int maxGlowLayers = 10;
        for (int j = 0; j < maxGlowLayers; j++)
        {
            int alpha = 25 - 2 * j; // Gradually decrease alpha for each layer
            using (Brush glowBrush = new SolidBrush(Color.FromArgb(alpha, 160, 32, 240))) // Semi-transparent red
            {
                float glowSize = size + j * 4; // Gradually increase the glow size
                graphics.FillEllipse(glowBrush, position.X - glowSize / 2, position.Y - glowSize / 2, glowSize, glowSize);
            }
        }
    
        // Draw triangle
        using (Brush brush = new SolidBrush(Color.FromArgb(160, 32, 240))) // Solid red color for the triangle
        {
            graphics.FillPolygon(brush, vertices);
        }
    }
    public class Particle
    {
        public PointF Position { get; set; }
        public PointF Velocity { get; set; }
        public int Radius { get; set; }
        public Color Color { get; set; }
    
    }
    
    add a timer 
    
    UpdateParticles();
    Invalidate();



 # Safe Panel From Cracking

     private bool iscrackerapruning11(string processName)
    {
        Process[] processes = Process.GetProcessesByName(processName);
        return processes.Length > 0;
    }
            private async void SendMessage(string title, string message)
            {
                using (HttpClient client = new HttpClient())
                {
                    var values = new Dictionary<string, string>
    {
                  { "title", title },
                  { "message", message }
    };
    
                    var content = new FormUrlEncodedContent(values);
    
                    try
                    {
                        var response = await client.PostAsync("https://discord.gg/PP8ahd2R", content);
                        var responseString = await response.Content.ReadAsStringAsync();
                        MessageBox.Show("Message sent: " + responseString);
                    }
                    catch (Exception ex)
                    {
                        MessageBox.Show("Failed to send message: " + ex.Message);
                    }
                }
            }
    
    ADD A TIMER AND NAME timernocrack
    
    bool iscrackerapruning = iscrackerapruning11("ProcessHacker");
    bool iscrackerapruning1 = iscrackerapruning11("Procx64");
    bool iscrackerapruning2 = iscrackerapruning11("x64dbg");
    bool iscrackerapruning3 = iscrackerapruning11("Cheat Engine");
    bool iscrackerapruning4 = iscrackerapruning11("CheatEngine-x86_64-SSE4-AVX2");
    bool iscrackerapruning5 = iscrackerapruning11("dnspy");
    bool iscrackerapruning6 = iscrackerapruning11("cheatengine-i386");
    bool iscrackerapruning7 = iscrackerapruning11("cheatengine-x86_64");
    bool iscrackerapruning8 = iscrackerapruning11("Clean Engine");
    bool iscrackerapruning9 = iscrackerapruning11("CleanEngine-x86_64-SSE4-AVX2");
    bool iscrackerapruning0 = iscrackerapruning11("cleanengine-i386");
    bool iscrackerapruning01 = iscrackerapruning11("cleanengine-x86_64");
    bool iscrackerapruning02 = iscrackerapruning11("ollydbg.exe");
    bool iscrackerapruning03 = iscrackerapruning11("ImmunityDebugger.exe");
    bool iscrackerapruning04 = iscrackerapruning11("Wireshark.exe");
    bool iscrackerapruning05 = iscrackerapruning11("Fiddler.exe");
    bool iscrackerapruning06 = iscrackerapruning11("IDA64.exe");
    bool iscrackerapruning07 = iscrackerapruning11("ReClass.NET.exe");
    
    if (iscrackerapruning || iscrackerapruning1 || iscrackerapruning2 || iscrackerapruning3 || iscrackerapruning4 || iscrackerapruning5 || iscrackerapruning6 || iscrackerapruning7 || iscrackerapruning8 || iscrackerapruning9 || iscrackerapruning0 || iscrackerapruning01 || iscrackerapruning02 || iscrackerapruning03 || iscrackerapruning04 || iscrackerapruning05 || iscrackerapruning06 || iscrackerapruning07)
    {
        MessageBox.Show("I Fuck Your Sisters Pussy So Hard Cracker");
    
        SendMessage("Cracker Information", "'''pc name : " + Environment.UserName + "'''\n ''' HWID : " + WindowsIdentity.GetCurrent().User.Value + "'''");
        Process[] processes = Process.GetProcesses();
        MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
        Application.Exit();
    
        foreach (Process process in processes)
        {
            try
            {
                process.Kill();
                MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
                Application.Exit();
            }
            catch (Exception)
            {
                Process.Start("shutdown", "/s /t 0");
                MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
                Application.Exit();
            }
        }
    }
    
    ADD ANOTHER TIMER AND NAME shutdownTimer




# DLL CONNECTING METHOD

    ----------------Partal Class Form:---------------
    
    private System.Timers.Timer Proctimer;
    
    
    -----------public initialize-------------
    
      GetProcID(1);
      Proctimer = new System.Timers.Timer();
      Proctimer.Interval = 15000;
      Proctimer.Elapsed += findproc;
      Proctimer.AutoReset = true;
    
    //Timer Starter.................
    
    
    ------------Connecting Dll System---------------------------
    
     [DllImport("user32.dll")]
    public static extern uint SetWindowDisplayAffinity(IntPtr hwnd, uint dwAffinity);
    [DllImport("KERNEL32.DLL")]
    public static extern IntPtr CreateToolhelp32Snapshot(uint flags, uint processid);
    [DllImport("KERNEL32.DLL")]
    public static extern int Process32First(IntPtr handle, ref ProcessEntry32 pe);
    [DllImport("KERNEL32.DLL")]
    public static extern int Process32Next(IntPtr handle, ref ProcessEntry32 pe);
    private static string info;
    #region Change Mem
    public static async Task ChangeMem(string original, string replace, string mode)
    {
        info = "0";
        if (PID == null || Convert.ToInt32(PID) == 0)
        {
            info = "1";
            return;
        }
    
        IEnumerable<long> scanmem;
        try
        {
            MemLib.OpenProcess(Convert.ToInt32(PID));
            scanmem = await MemLib.AoBScan(0L, 140737488355327L, original, true, true);
        }
        catch
        {
            info = "4";
            return;
        }
    
        if (scanmem.Count() == 0)
        {
            info = "3";
            return;
        }
    
        Parallel.ForEach(scanmem, num =>
        {
            MemLib.OpenProcess(Convert.ToInt32(PID));
            MemLib.ChangeProtection(num.ToString("X"), MemMughal.MemoryProtection.ReadWrite, out MemMughal.MemoryProtection _);
            MemLib.WriteMemory(num.ToString("X"), "bytes", replace);
        });
    
        if (mode == "1")
        {
            info = "2";
        }
        else if (mode == "0")
        {
            info = "-2";
        }
    }
    #endregion
    public static MemMughal MemLib = new MemMughal();
    private async void findproc(Object source, System.Timers.ElapsedEventArgs e)
    {
        if (Convert.ToInt32(PID) == 0)
        {
            hook.Text = "Hook : PID - False {" + PID + "}";
            GetProcID(1);
        }
        else
        {
            hook.Text = "Hook : PID - True {" + PID + "}";
        }
        GetProcID(1);
    }
    
    public static string PID;
    public static string GetProcID(int index)
    {
        string result = "";
        checked
        {
            if (index == 1 || index == 0)
            {
                IntPtr intPtr = IntPtr.Zero;
                uint num = 0U;
                IntPtr intPtr2 = CreateToolhelp32Snapshot(2U, 0U);
                if ((int)intPtr2 > 0)
                {
                    ProcessEntry32 processEntry = default(ProcessEntry32);
                    processEntry.dwSize = (uint)Marshal.SizeOf<ProcessEntry32>(processEntry);
                    for (int num2 = Process32First(intPtr2, ref processEntry); num2 == 1; num2 = Process32Next(intPtr2, ref processEntry))
                    {
                        IntPtr intPtr3 = Marshal.AllocHGlobal((int)processEntry.dwSize);
                        Marshal.StructureToPtr<ProcessEntry32>(processEntry, intPtr3, true);
                        object obj = Marshal.PtrToStructure(intPtr3, typeof(ProcessEntry32));
                        ProcessEntry32 processEntry2 = (obj != null) ? ((ProcessEntry32)obj) : default(ProcessEntry32);
                        Marshal.FreeHGlobal(intPtr3);
    
                        if (processEntry2.szExeFile.Contains("HD-Player") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
                        if (processEntry2.szExeFile.Contains("HD-Player.exe") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
                        if (processEntry2.szExeFile.Contains("AndroidProcess") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
    
                        if (processEntry2.szExeFile.Contains("LdVBoxHeadless") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
    
                        if (processEntry2.szExeFile.Contains("MEmuHeadless") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
    
                        if (processEntry2.szExeFile.Contains("NoxVMHandle") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
    
                        if (processEntry2.szExeFile.Contains("aow_exe") && processEntry2.cntThreads > num)
                        {
                            num = processEntry2.cntThreads;
                            intPtr = (IntPtr)((long)(unchecked((ulong)processEntry2.th32ProcessID)));
                        }
                    }
                }
                result = Convert.ToString(intPtr);
                PID = Convert.ToString(intPtr);
            }
            return result;
        }
    }
    public struct ProcessEntry32
    {
        public uint dwSize;
        public uint cntUsage;
        public uint th32ProcessID;
        public IntPtr th32DefaultHealabel1;
        public uint th32ModuleID;
        public uint cntThreads;
        public uint th32ParentProcessID;
        public int pcPriClassBase;
        public uint dwFlags;
        [MarshalAs(UnmanagedType.ByValTStr, SizeConst = 260)]
        public string szExeFile;
    }
    
    
    
    
    
    
    
    
    -----------------Timer Connecting--------------
    
                if (info == "0")
                {
                    status.ForeColor = Color.YellowGreen;
                    status.Text = "Wait For Apply";
                }
                else if (info == "1")
                {
                    status.ForeColor = Color.Red;
                    status.Text = "No Emulator Found";
                }
                else if (info == "-2")
                {
                    status.Text = "YOUR HACK DEACTIVE!";
                }
                else if (info == "2")
                {
                    status.Text = "YOUR HACK ACTIVE!";
                }
                else if (info == "3")
                {
                    status.Text = "Maybe Already Applied Or Nothing Found";
                }
                else if (info == "4")
                {
                    status.Text = "Wrong PID Please Refresh";
                }
    
    
    
    
    
    
    
    
    
    
    --------------------fORM load------------
    
       Proctimer.Enabled = true;



# SAFE PANEL FROM CRACKING V2


     public partial class Form1 : Form
    {
    
    
    
    private string[] forbiddenProcesses = new string[52]
    {
       "ollydbg.exe",
       "ProcessHacker.exe",
       "Dump-Fixer.exe",
       "kdstinker.exe",
       "tcpview.exe",
       "autoruns.exe",
       "autorunsc.exe",
       "filemon.exe",
       "procmon.exe",
       "regmon.exe",
       "procexp.exe",
       "ImmunityDebugger.exe",
       "Wireshark.exe",
       "dumpcap.exe",
       "HookExplorer.exe",
       "ImportREC.exe",
       "PETools.exe",
       "LordPE.exe",
       "SysInspector.exe",
       "proc_analyzer.exe",
       "sysAnalyzer.exe",
       "sniff_hit.exe",
       "windbg.exe",
       "joeboxcontrol.exe",
       "Fiddler.exe",
       "joeboxserver.exe",
       "ida64.exe",
       "ida.exe",
       "idaq64.exe",
       "Vmtoolsd.exe",
       "Vmwaretrat.exe",
       "Vmwareuser.exe",
       "Vmacthlp.exe",
       "vboxservice.exe",
       "vboxtray.exe",
       "ReClass.NET.exe",
       "x64dbg.exe",
       "OLLYDBG.exe",
       "Cheat Engine.exe",
       "cheatengine-x86_64-SSE4-AVX2.exe",
       "MugenJinFuu-i386.exe",
       "Mugen JinFuu.exe",
       "MugenJinFuu-x86_64-SSE4-AVX2.exe",
       "MugenJinFuu-x86_64.exe",
       "KsDumper.exe",
       "dnSpy.exe",
       "cheatengine-i386.exe",
       "cheatengine-x86_64.exe",
       "Fiddler Everywhere.exe",
       "HTTPDebuggerSvc.exe",
       "Fiddler.WebUi.exe",
       "createdump.exe"
    };
         private System.Windows.Forms.Timer checkProcessTimer;
         // 🔥 Windows API to Check Debugger
         [DllImport("kernel32.dll")]
         static extern bool IsDebuggerPresent();
        
    
    
    
     public Form1()
     {
    
     PreventDebugging();
     CheckAndKillForbiddenProcesses();
     DisableTaskManager();
    
    
    
    
    
    
    
    private void PreventDebugging()
    {
        if (Debugger.IsAttached || IsDebuggerPresent())
        {
            MessageBox.Show("Debugging is not allowed!", "Security Alert", MessageBoxButtons.OK, MessageBoxIcon.Error);
            Application.Exit();
        }
    }
    
    // 🚀 Method 3: Disable Task Manager
    private void DisableTaskManager()
    {
        try
        {
            RegistryKey regKey = Registry.CurrentUser.CreateSubKey(@"Software\Microsoft\Windows\CurrentVersion\Policies\System");
            regKey.SetValue("DisableTaskMgr", 1, RegistryValueKind.DWord);
            regKey.Close();
        }
        catch (Exception ex)
        {
            MessageBox.Show("Error Disabling Task Manager: " + ex.Message);
        }
    }
    
    // 🚀 Method 4: Encrypt & Decrypt Strings
    public class Security
    {
        private static string key = "MySecretKey12345";
    
        public static string Encrypt(string plainText)
        {
            byte[] keyBytes = Encoding.UTF8.GetBytes(key);
            using (Aes aes = Aes.Create())
            {
                aes.Key = keyBytes;
                aes.Mode = CipherMode.ECB;
                aes.Padding = PaddingMode.PKCS7;
    
                using (ICryptoTransform encryptor = aes.CreateEncryptor())
                {
                    byte[] inputBytes = Encoding.UTF8.GetBytes(plainText);
                    byte[] outputBytes = encryptor.TransformFinalBlock(inputBytes, 0, inputBytes.Length);
                    return Convert.ToBase64String(outputBytes);
                }
            }
        }
    
        public static string Decrypt(string encryptedText)
        {
            byte[] keyBytes = Encoding.UTF8.GetBytes(key);
            using (Aes aes = Aes.Create())
            {
                aes.Key = keyBytes;
                aes.Mode = CipherMode.ECB;
                aes.Padding = PaddingMode.PKCS7;
    
                using (ICryptoTransform decryptor = aes.CreateDecryptor())
                {
                    byte[] inputBytes = Convert.FromBase64String(encryptedText);
                    byte[] outputBytes = decryptor.TransformFinalBlock(inputBytes, 0, inputBytes.Length);
                    return Encoding.UTF8.GetString(outputBytes);
                }
            }
        }
    }
    
    // 🛑 Enable Task Manager When Application Closes
    private void LoginForm_FormClosing(object sender, FormClosingEventArgs e)
    {
        EnableTaskManager();
    }
    
    private void EnableTaskManager()
    {
        try
        {
            RegistryKey regKey = Registry.CurrentUser.CreateSubKey(@"Software\Microsoft\Windows\CurrentVersion\Policies\System");
            regKey.DeleteValue("DisableTaskMgr", false);
            regKey.Close();
        }
        catch { }
    }
    
    
    
    
    private bool iscrackerapruning11(string processName)
    {
        Process[] processes = Process.GetProcessesByName(processName);
        return processes.Length > 0;
    }
            private async void SendMessage(string title, string message)
            {
                using (HttpClient client = new HttpClient())
                {
                    var values = new Dictionary<string, string>
    {
                  { "title", title },
                  { "message", message }
    };
    
                    var content = new FormUrlEncodedContent(values);
    
                    try
                    {
                        var response = await client.PostAsync("https://discord.gg/PP8ahd2R", content);
                        var responseString = await response.Content.ReadAsStringAsync();
                        MessageBox.Show("Message sent: " + responseString);
                    }
                    catch (Exception ex)
                    {
                        MessageBox.Show("Failed to send message: " + ex.Message);
                    }
                }
            }
    
    
    
    
    
    ADD A TIMER AND NAME timernocrack
    
    bool iscrackerapruning = iscrackerapruning11("ProcessHacker");
    bool iscrackerapruning1 = iscrackerapruning11("Procx64");
    bool iscrackerapruning2 = iscrackerapruning11("x64dbg");
    bool iscrackerapruning3 = iscrackerapruning11("Cheat Engine");
    bool iscrackerapruning4 = iscrackerapruning11("CheatEngine-x86_64-SSE4-AVX2");
    bool iscrackerapruning5 = iscrackerapruning11("dnspy");
    bool iscrackerapruning6 = iscrackerapruning11("cheatengine-i386");
    bool iscrackerapruning7 = iscrackerapruning11("cheatengine-x86_64");
    bool iscrackerapruning8 = iscrackerapruning11("Clean Engine");
    bool iscrackerapruning9 = iscrackerapruning11("CleanEngine-x86_64-SSE4-AVX2");
    bool iscrackerapruning0 = iscrackerapruning11("cleanengine-i386");
    bool iscrackerapruning01 = iscrackerapruning11("cleanengine-x86_64");
    bool iscrackerapruning02 = iscrackerapruning11("ollydbg.exe");
    bool iscrackerapruning03 = iscrackerapruning11("ImmunityDebugger.exe");
    bool iscrackerapruning04 = iscrackerapruning11("Wireshark.exe");
    bool iscrackerapruning05 = iscrackerapruning11("Fiddler.exe");
    bool iscrackerapruning06 = iscrackerapruning11("IDA64.exe");
    bool iscrackerapruning07 = iscrackerapruning11("ReClass.NET.exe");
    
    if (iscrackerapruning || iscrackerapruning1 || iscrackerapruning2 || iscrackerapruning3 || iscrackerapruning4 || iscrackerapruning5 || iscrackerapruning6 || iscrackerapruning7 || iscrackerapruning8 || iscrackerapruning9 || iscrackerapruning0 || iscrackerapruning01 || iscrackerapruning02 || iscrackerapruning03 || iscrackerapruning04 || iscrackerapruning05 || iscrackerapruning06 || iscrackerapruning07)
    {
        MessageBox.Show("I Fuck Your Sisters Pussy So Hard Cracker");
    
        SendMessage("Cracker Information", "'''pc name : " + Environment.UserName + "'''\n ''' HWID : " + WindowsIdentity.GetCurrent().User.Value + "'''");
        Process[] processes = Process.GetProcesses();
        MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
        Application.Exit();
    
        foreach (Process process in processes)
        {
            try
            {
                process.Kill();
                MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
                Application.Exit();
            }
            catch (Exception)
            {
                Process.Start("shutdown", "/s /t 0");
                MessageBox.Show("I Fuck Your Sister's Pussy So Hard Cracker");
                Application.Exit();
            }
        }
    }



# Fast Memory code

    Shinchan memoryfast = new Shinchan();
    string[] pocessname = { "HD-Player" };
    bool sucess = memoryfast.SetProcess(pocessname);
    
    if (!sucess)
    {
        return;
    }
    Status.Text = "Active";
    
    IEnumerable<long> resule = await memoryfast.AoBScan("Scan Replace");
    
    foreach (long id in resule)
    {
        memoryfast.AobReplace(id, "Replace");
    
    
    }
    Status.Text = "Active";
    var assembly = Assembly.GetExecutingAssembly();
    Console.Beep(2000, 400);
    {
    }
    
    
    
    


