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
# IN ON AND OFF SIWTCH BUTTON CODE

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

