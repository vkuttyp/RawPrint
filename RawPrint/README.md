RawPrint
========

.Net library to send files directly to a Windows printer bypassing the printer driver.

Send PostScript, PCL or other print file types directly to a printer.

Requires .Net 4 runtime on Windows XP to 8.1 and Server 2003 to 2012.

Usage:

	using RawPrint;
	
	Printer.PrintFile("Printer Name", "C:\Path\To\Print\File.prn", "Document Name");