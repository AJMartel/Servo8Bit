
Servo8Bit
=========

This is a fork of the original repo: [https://github.com/fri000/Servo8Bit](https://github.com/fri000/Servo8Bit)

This version has been modified to work as an Arduino Library.


How To Install
--------------

Install this like a regulare Arduino Library. For further information please refer to this guide: [http://arduino.cc/en/Guide/Libraries](http://arduino.cc/en/Guide/Libraries)


Version History
---------------

 * **V0.7**	
 	* Bug fix: If detach() was called on a servo then subsequent calls to attach() would fail.
          The detach() function now works properly.
 * **V0.6** 
    * Added ability to easily select if this driver should use timer0 or
	  timer1.
	* Timer1 is now the default timer used. Used to be timer0.
	* Made the timer init happen later to allow this driver to work when
	  used with an attiny arduino library.
	* Fixed bug where a 512 microsecond pulse would not be generated.
 * **V0.5**
 	* Initial public release


