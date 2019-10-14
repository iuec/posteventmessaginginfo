<dl>

  <dt>
    <a name="cda">CDA</a>
  </dt>
  <dd>
    <b>C</b>linical <b>D</b>ocument <b>A</b>rchitecture
    <br>
    <br>
    This is a set of standards for HL7 messages. It provides structure and integrity to messages transmitted from one computer system to another. The system receiving the messages uses the standard to inspect the message and understand how it's structured. The quality of content in the messages effects how useful they are to receiving systems.
  </dd>

  <dt>
    <a name="dos">DOS</a>
  </dt>
  <dd>
    <b>D</b>irectory <b>O</b>f <b>S</b>ervices
  </dd>

  <dt>
    <a name="disposition">Disposition</a>
  </dt>
  <dd>
    A disposition is a ....
  </dd>

  <dt>
    <a name="dts">DTS</a>
  </dt>
  <dd>
    <b>D</b>ata <b>T</b>ransfer <b>S</b>ervice
    <br><br>
    This is a mechanism for moving data, typically Kettering messages, from one computer system to another. It works much the same way as email, where a sending system sends the message to a central server which stores it until it is retrieved by the receiving system. The receiving systems usually retrieve messages by 8.00am the next day.
  </dd>

  <dt><a name="hscic">HSCIC</a></dt>
  <dd>
    <b>H</b>ealth and <b>S</b>ocial <b>C</b>are <b>I</b>nformation <b>C</b>entre
  <dd>

  <dt>ITK</dt>
  <dd>
    <b>I</b>nteroperability <b>T</b>ool <b>K</b>it
    <br><br>
    Interoperability Tool Kit. This is a standard for moving messages from one computer system to another and is an alternative to DTS. NHS 111 uses a subset of the ITK standards for sending information.
    <br><br>
    The NHS 111 implementation is synchronous, which means that the sending system is notified when a message has been successfully delivered, after the receiving system has acknowledged that is has the data in real time. DTS is unable to do this as it uses an intermediary server.
  </dd>

  <dt><a name="kettering">Kettering</a></dt>
  <dd>
    Kettering is a standard message format that Out of Hours services use to report back to GP’s.
    <br><br>
    The standard has not been maintained and there are now many variants of it in use. Providers do not know which version of the Kettering template is being used where, and therefore can't send electronic PEMs to practices that are out of their core area. In these circumstances, PEM tends to fall back to fax.
  </dd>

  <dt><a name="nqr">NQR</a></dt>
    <dd><b>N</b>ational <b>Q</b>uality <b>R</b>equirement
    <br><br>
  <dd>

  <dt><a name="out-of-area">Out Of Area</a></dt>
  <dd>
  'Out of area' is used to describe a situation where a patient is being looked after by a service which is not commissioned to provide services to the area in which the patient is registered with a GP surgery - also known as the patient's 'Home Area'.
  <br><br>
  Some examples of when a patient might be considered 'out of area' are:
  <br><br>
  <ul>
    <li>The patient has accessed a service (e.g. NHS 111) whilst located away from their usual home while traveling</li>
    <li>The patient has called NHS 111 and their call has not been routed to the service providing NHS 111 to their home area</li>
  </ul>
  </dd>

  <dt><a name="ooh">OOH</a></dt>
  <dd>
    <b>O</b>ut <b>O</b>f <b>H</b>ours or <b>O</b>ut <b>O</b>f <b>H</b>ospital
    <br><br>
  </dd>

  <dt><a name="pem">PEM</a></dt>
  <dd>
    <b>P</b>ost <b>E</b>vent <b>M</b>essaging
    <br>
    <br>
    In the context of NHS 111 is an electronic document that is transmitted to GP practices at the end of an NHS 111 contact to notifiy that a contact has taken place.

    There are essentially two types of PEM a GP can receive:<br><br>
    <ul>
      <li>‘For Action’ meaning a GP has been referred back to their own GP with a timeframe associated with it</li>
      <li>‘For Your Information’ message which is for the GP to inspect and file against the patients record.</li>
    </ul>
  <dd>

  <dt><a name="renderedpem">Rendered PEM</a></dt>
  <dd>
    Rendered PEM means 'Rendered Post Event Message'.
    <br>
    <br>
    This refers to a CDA document which has been converted from XML format (designed for processing by software) to a human-readable format such as PDF or HTML.
    <br>
    <br>
    <a href="../technical_faq#renderedpem">Full Explanation of Rendered PEM</a>
  <dd>

  <dt><a name="trud">TRUD</a></dt>
  <dd>
    <b>T</b>erminology <b>R</b>eference data <b>U</b>pdate <b>D</b>istribution site
    <br><br>
    This is a website that the Health and Social Care Information Centre uses to distribute specifications and resources to be used for NHS Information Technology
    <br><br>
    For example:
    <br><br>
    <ul>
      <li>Messaging Specifications</li>
      <li>Clinical Code Lists</li>
      <li>Accreditation Guidance</li>
    </ul>
    You can access the TRUD Website here: <a href="https://isd.hscic.gov.uk/">https://isd.hscic.gov.uk</a>
  <dd>

</dl>
