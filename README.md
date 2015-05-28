CodeIgniter-PDF-Generator-Library
=================================

_Deprecated: Looking for a new maintainer for this package. Open an issue if interested._

Generate PDF's in CodeIgniter using this easy to use library based on domPDF.

Installation
============
1. Drop the pdf.php library into your libraries directory.
2. Download domPDF from [http://code.google.com/p/dompdf/downloads/list](http://code.google.com/p/dompdf/downloads/list)
3. Drop the dompdf directory into your libraries directory alongside the pdf.php file.

Usage
=====
You can convert a view into a PDF by using the following code.

	$this->load->library('pdf');
	$this->pdf->load_view('welcome');
	$this->pdf->render();
	$this->pdf->stream("welcome.pdf");

You can also pass in data to the function just as you would using `$this->load->view('welcome', $data);` by using

	$this->pdf->load_view('welcome', $data);

Help
====
For more information on how to use domPDF then please visit: [http://code.google.com/p/dompdf/wiki/Usage](http://code.google.com/p/dompdf/wiki/Usage)

License
=======
* CodeIgniter PDF Library - MIT License
* domPDF - GNU Lesser GPL

Credits
=======
* CodeIngiter Conversion - [Chris Harvey](http://www.chrisnharvey.com)
* domPDF - [The domPDF Team](http://code.google.com/p/dompdf/)
