# Climograph

 Steven Black<br />Project home: https://github.com/StevenBlack/climographs

## Introduction

 The motivation for this repository is, given a location, create its clomograph.

 See: https://en.wikipedia.org/wiki/Climograph.

### Static Examples (these are images)

 **Example: **You can pass a single location Entity and get its climograph.

<p class="Input">
 <img src="HTMLFiles/climograph_1.png" alt="climograph_1.png" width="4" height="17" style="vertical-align:middle" />
</p>

<p class="Input">
 <img src="HTMLFiles/climograph_2.gif" alt="climograph_2.gif" width="427" height="545" style="vertical-align:middle" />
</p>

<p class="Input">
 <img src="HTMLFiles/climograph_3.png" alt="climograph_3.png" width="4" height="17" style="vertical-align:middle" />
</p>

 **Example: **You can pass a list of location Entities and get a list of their climographs.

 <span><span><img src="HTMLFiles/climograph_4.gif" alt="climograph_4.gif" width="798" height="631" style="vertical-align:middle" /></span></span>

## The Code

<p class="Input">
 <img src="HTMLFiles/climograph_5.gif" alt="climograph_5.gif" width="840" height="2139" style="vertical-align:middle" />
</p>

## Live Examples

### Example 1 &mdash; default climograph

 This call with no options produces a default climograph.

<p class="Input">
 <img src="HTMLFiles/climograph_6.png" alt="climograph_6.png" width="204" height="27" style="vertical-align:middle" />
</p>

<p class="Output">
 <img src="HTMLFiles/climograph_7.gif" alt="climograph_7.gif" width="360" height="489" style="vertical-align:middle;" usemap="#map_7" />
<map name="map_7">
<area shape="rect" coords="288,438,305,339" title="max      32.64

75%      27.8426

median   13.4505

25%      3.36262

min      0." nohref="" />
<area shape="rect" coords="268,438,285,294" title="max      48.

75%      40.1372

median   16.5488

25%      4.1372

min      0." nohref="" />
<area shape="rect" coords="248,438,265,336" title="max      33.64

75%      27.8268

median   10.3873

25%      2.59683

min      0." nohref="" />
<area shape="rect" coords="227,438,244,370" title="max      22.02

75%      17.7245

median   4.8378

25%      1.20945

min      0." nohref="" />
<area shape="rect" coords="207,438,224,387" title="max      16.17

75%      12.8734

median   2.98366

25%      0.745915

min      0." nohref="" />
<area shape="rect" coords="187,438,204,413" title="max      7.3

75%      6.06573

median   2.36293

25%      0.590732

min      0." nohref="" />
<area shape="rect" coords="167,438,184,398" title="max      12.57

75%      10.4329

median   4.02171

25%      1.00543

min      0." nohref="" />
<area shape="rect" coords="147,438,164,389" title="max      15.52

75%      13.0131

median   5.49244

25%      1.37311

min      0." nohref="" />
<area shape="rect" coords="127,438,144,382" title="max      17.88

75%      15.2344

median   7.2975

25%      1.82438

min      0." nohref="" />
<area shape="rect" coords="107,438,124,329" title="max      35.96

75%      29.6587

median   10.7548

25%      2.68869

min      0." nohref="" />
<area shape="rect" coords="87,438,103,375" title="max      20.28

75%      17.1571

median   7.78825

25%      1.94706

min      0." nohref="" />
<area shape="rect" coords="66,438,83,325" title="max      37.26

75%      31.4929

median   14.1917

25%      3.54793

min      0." nohref="" />
<area shape="rect" coords="288,248,305,208" title="max      6.28

75%      5.89482

median   4.73927

25%      1.81482

min      0.84" nohref="" />
<area shape="rect" coords="268,242,285,186" title="max      9.52

75%      8.94762

median   7.23049

25%      3.15012

min      1.79" nohref="" />
<area shape="rect" coords="248,190,265,163" title="max      12.94

75%      12.4335

median   10.9139

25%      9.81598

min      9.45" nohref="" />
<area shape="rect" coords="227,160,244,137" title="max      16.76

75%      16.3821

median   15.2483

25%      14.1846

min      13.83" nohref="" />
<area shape="rect" coords="207,142,224,114" title="max      20.12

75%      19.6805

median   18.362

25%      16.883

min      16.39" nohref="" />
<area shape="rect" coords="187,146,204,107" title="max      21.1

75%      20.4025

median   18.31

25%      16.495

min      15.89" nohref="" />
<area shape="rect" coords="167,159,184,125" title="max      18.56

75%      17.8796

median   15.8385

25%      14.4521

min      13.99" nohref="" />
<area shape="rect" coords="147,186,164,147" title="max      15.28

75%      14.7652

median   13.2207

25%      10.8352

min      10.04" nohref="" />
<area shape="rect" coords="127,213,144,168" title="max      12.24

75%      11.6393

median   9.83732

25%      7.01933

min      6.08" nohref="" />
<area shape="rect" coords="107,221,124,187" title="max      9.4

75%      8.87933

median   7.31732

25%      5.47433

min      4.86" nohref="" />
<area shape="rect" coords="87,250,103,194" title="max      8.36

75%      7.62268

median   5.41073

25%      1.81018

min      0.61" nohref="" />
<area shape="rect" coords="66,251,83,198" title="max      7.8

75%      7.0672

median   4.86878

25%      1.5472

min      0.44" nohref="" />
</map>
</p>

 

### Example 2 &mdash; normalizing scales across climographs

 This call uses options to set the background color, and normalizes the vertical ranges for both the temperature and precipitation plots .

 

<p class="Input">
 <img src="HTMLFiles/climograph_8.png" alt="climograph_8.png" width="327" height="119" style="vertical-align:middle" />
</p>

<p class="Output">
 <img src="HTMLFiles/climograph_9.gif" alt="climograph_9.gif" width="749" height="491" style="vertical-align:middle;" usemap="#map_9" />
<map name="map_9">
<area shape="rect" coords="669,446,686,403" title="max      12.71

75%      10.6757

median   4.57282

25%      1.14321

min      0." nohref="" />
<area shape="rect" coords="649,446,666,414" title="max      9.3

75%      7.92632

median   3.80526

25%      0.951316

min      0." nohref="" />
<area shape="rect" coords="629,446,646,387" title="max      18.04

75%      14.6893

median   4.6373

25%      1.15932

min      0." nohref="" />
<area shape="rect" coords="608,446,625,387" title="max      18.02

75%      14.4482

median   3.73297

25%      0.933243

min      0." nohref="" />
<area shape="rect" coords="588,446,605,410" title="max      10.45

75%      8.77243

median   3.73972

25%      0.934931

min      0." nohref="" />
<area shape="rect" coords="568,446,585,409" title="max      10.99

75%      9.22764

median   3.94056

25%      0.985139

min      0." nohref="" />
<area shape="rect" coords="548,446,565,392" title="max      16.51

75%      13.589

median   4.82583

25%      1.20646

min      0." nohref="" />
<area shape="rect" coords="528,446,545,332" title="max      35.86

75%      28.3655

median   5.88184

25%      1.47046

min      0." nohref="" />
<area shape="rect" coords="508,446,525,412" title="max      9.83

75%      8.07276

median   2.80103

25%      0.700256

min      0." nohref="" />
<area shape="rect" coords="488,446,505,404" title="max      12.42

75%      10.2819

median   3.86744

25%      0.966859

min      0." nohref="" />
<area shape="rect" coords="468,446,484,410" title="max      10.71

75%      8.85919

median   3.30676

25%      0.826689

min      0." nohref="" />
<area shape="rect" coords="447,446,464,407" title="max      11.44

75%      9.48145

median   3.60579

25%      0.901447

min      0." nohref="" />
<area shape="rect" coords="669,255,686,206" title="max      9.65

75%      8.57305

median   5.3422

25%      1.92055

min      0.78" nohref="" />
<area shape="rect" coords="649,238,666,196" title="max      11.72

75%      10.7649

median   7.89951

25%      4.98988

min      4.02" nohref="" />
<area shape="rect" coords="629,209,646,175" title="max      15.68

75%      14.8902

median   12.5207

25%      10.3977

min      9.69" nohref="" />
<area shape="rect" coords="608,187,625,156" title="max      19.36

75%      18.6371

median   16.4683

25%      14.5346

min      13.89" nohref="" />
<area shape="rect" coords="588,175,605,132" title="max      24.12

75%      23.0732

median   19.9327

25%      17.2532

min      16.36" nohref="" />
<area shape="rect" coords="568,174,585,133" title="max      23.86

75%      22.9446

median   20.1983

25%      17.3346

min      16.38" nohref="" />
<area shape="rect" coords="548,200,565,148" title="max      20.98

75%      20.1701

median   17.7402

25%      13.0076

min      11.43" nohref="" />
<area shape="rect" coords="528,201,545,165" title="max      17.57

75%      16.8551

median   14.7102

25%      12.1826

min      11.34" nohref="" />
<area shape="rect" coords="508,218,525,179" title="max      14.9

75%      13.935

median   11.04

25%      8.655

min      7.86" nohref="" />
<area shape="rect" coords="488,235,505,199" title="max      11.06

75%      10.3446

median   8.19829

25%      5.60457

min      4.74" nohref="" />
<area shape="rect" coords="468,266,484,208" title="max      9.41

75%      8.3272

median   5.07878

25%      0.234695

min      -1.38" nohref="" />
<area shape="rect" coords="447,268,464,215" title="max      8.07

75%      7.19561

median   4.57244

25%      -0.18439

min      -1.77" nohref="" />
<area shape="rect" coords="296,444,313,377" title="max      21.21

75%      18.2195

median   9.24805

25%      2.71701

min      0.54" nohref="" />
<area shape="rect" coords="276,441,293,372" title="max      22.79

75%      19.1977

median   8.42073

25%      3.33518

min      1.64" nohref="" />
<area shape="rect" coords="256,444,273,357" title="max      27.61

75%      22.8359

median   8.51341

25%      2.50335

min      0.5" nohref="" />
<area shape="rect" coords="235,442,252,368" title="max      24.15

75%      20.2376

median   8.50049

25%      3.04012

min      1.22" nohref="" />
<area shape="rect" coords="215,444,232,307" title="max      43.71

75%      35.1257

median   9.37268

25%      2.75567

min      0.55" nohref="" />
<area shape="rect" coords="195,446,212,351" title="max      29.73

75%      24.6722

median   9.49878

25%      2.3897

min      0.02" nohref="" />
<area shape="rect" coords="175,446,192,366" title="max      24.8

75%      20.8544

median   9.01756

25%      2.26939

min      0.02" nohref="" />
<area shape="rect" coords="155,443,172,358" title="max      27.46

75%      22.9513

median   9.42512

25%      2.91128

min      0.74" nohref="" />
<area shape="rect" coords="135,441,152,363" title="max      25.89

75%      21.7263

median   9.23537

25%      3.32884

min      1.36" nohref="" />
<area shape="rect" coords="115,444,132,372" title="max      22.74

75%      19.3341

median   9.11634

25%      2.67659

min      0.53" nohref="" />
<area shape="rect" coords="95,442,111,396" title="max      14.98

75%      12.8215

median   6.3461

25%      2.50902

min      1.23" nohref="" />
<area shape="rect" coords="74,442,91,380" title="max      20.27

75%      17.155

median   7.81

25%      2.8525

min      1.2" nohref="" />
<area shape="rect" coords="296,275,313,205" title="max      9.86

75%      8.28939

median   3.57756

25%      -1.44561

min      -3.12" nohref="" />
<area shape="rect" coords="276,231,293,200" title="max      10.97

75%      10.373

median   8.58195

25%      6.29299

min      5.53" nohref="" />
<area shape="rect" coords="256,200,273,168" title="max      17.08

75%      16.3554

median   14.1815

25%      12.1629

min      11.49" nohref="" />
<area shape="rect" coords="235,164,252,141" title="max      22.25

75%      21.7211

median   20.1344

25%      18.8261

min      18.39" nohref="" />
<area shape="rect" coords="215,144,232,126" title="max      25.27

75%      24.8595

median   23.6278

25%      22.557

min      22.2" nohref="" />
<area shape="rect" coords="195,145,212,124" title="max      25.62

75%      25.2343

median   24.0773

25%      22.6093

min      22.12" nohref="" />
<area shape="rect" coords="175,161,192,138" title="max      22.94

75%      22.3923

median   20.7493

25%      19.4823

min      19.06" nohref="" />
<area shape="rect" coords="155,190,172,161" title="max      18.49

75%      17.7341

median   15.4666

25%      13.9016

min      13.38" nohref="" />
<area shape="rect" coords="135,221,152,193" title="max      12.18

75%      11.6824

median   10.1895

25%      8.08988

min      7.39" nohref="" />
<area shape="rect" coords="115,247,132,215" title="max      8.01

75%      7.26317

median   5.02268

25%      3.00317

min      2.33" nohref="" />
<area shape="rect" coords="95,279,111,234" title="max      4.24

75%      3.57244

median   1.56976

25%      -2.56256

min      -3.94" nohref="" />
<area shape="rect" coords="74,279,91,236" title="max      4.01

75%      3.15183

median   0.577317

25%      -2.72067

min      -3.82" nohref="" />
</map>
</p>

 

### <span class="SubsectionInline">Example 3 &mdash; omit joining bars</span>

 This call uses options to omit the lines joining temperature and precipitation mean values .

 

<p class="Input">
 <img src="HTMLFiles/climograph_10.png" alt="climograph_10.png" width="623" height="27" style="vertical-align:middle" />
</p>

<p class="Output">
 <img src="HTMLFiles/climograph_11.gif" alt="climograph_11.gif" width="360" height="474" style="vertical-align:middle;" usemap="#map_11" />
<map name="map_11">
<area shape="rect" coords="283,423,300,358" title="max      11.58

75%      9.30086

median   2.46343

25%      0.615857

min      0." nohref="" />
<area shape="rect" coords="264,423,280,360" title="max      11.07

75%      9.13331

median   3.32324

25%      0.830809

min      0." nohref="" />
<area shape="rect" coords="245,423,261,327" title="max      17.28

75%      14.1546

median   4.77829

25%      1.19457

min      0." nohref="" />
<area shape="rect" coords="225,423,242,303" title="max      21.6

75%      17.1623

median   3.84917

25%      0.962292

min      0." nohref="" />
<area shape="rect" coords="206,423,223,303" title="max      21.59

75%      17.6476

median   5.82029

25%      1.45507

min      0." nohref="" />
<area shape="rect" coords="187,423,203,286" title="max      24.83

75%      19.7261

median   4.41444

25%      1.10361

min      0." nohref="" />
<area shape="rect" coords="168,423,184,304" title="max      21.46

75%      17.3749

median   5.11972

25%      1.27993

min      0." nohref="" />
<area shape="rect" coords="148,423,165,312" title="max      19.97

75%      16.3758

median   5.59324

25%      1.39831

min      0." nohref="" />
<area shape="rect" coords="129,423,146,332" title="max      16.27

75%      13.3667

median   4.65667

25%      1.16417

min      0." nohref="" />
<area shape="rect" coords="110,423,126,347" title="max      13.55

75%      10.7818

median   2.47722

25%      0.619306

min      0." nohref="" />
<area shape="rect" coords="91,423,107,372" title="max      9.01

75%      7.22115

median   1.85459

25%      0.463649

min      0." nohref="" />
<area shape="rect" coords="71,423,88,378" title="max      7.79

75%      6.37993

median   2.14973

25%      0.537432

min      0." nohref="" />
<area shape="rect" coords="283,238,300,187" title="max      5.14

75%      3.63268

median   -0.889268

25%      -6.24482

min      -8.03" nohref="" />
<area shape="rect" coords="264,203,280,169" title="max      10.18

75%      9.01018

median   5.50073

25%      2.51518

min      1.52" nohref="" />
<area shape="rect" coords="245,178,261,148" title="max      15.82

75%      14.9429

median   12.3117

25%      9.53543

min      8.61" nohref="" />
<area shape="rect" coords="225,151,242,126" title="max      22.06

75%      21.3657

median   19.2829

25%      16.7607

min      15.92" nohref="" />
<area shape="rect" coords="206,133,223,108" title="max      26.75

75%      25.8895

median   23.3078

25%      21.352

min      20.7" nohref="" />
<area shape="rect" coords="187,130,203,106" title="max      27.38

75%      26.5952

median   24.241

25%      22.2602

min      21.6" nohref="" />
<area shape="rect" coords="168,144,184,117" title="max      24.3

75%      23.5715

median   21.3859

25%      18.689

min      17.79" nohref="" />
<area shape="rect" coords="148,163,165,134" title="max      19.84

75%      18.853

median   15.8922

25%      13.4455

min      12.63" nohref="" />
<area shape="rect" coords="129,192,146,160" title="max      12.7

75%      11.972

median   9.78805

25%      5.98701

min      4.72" nohref="" />
<area shape="rect" coords="110,212,126,165" title="max      11.28

75%      9.39567

median   3.74268

25%      0.298171

min      -0.85" nohref="" />
<area shape="rect" coords="91,236,107,192" title="max      3.86

75%      2.46201

median   -1.73195

25%      -5.93799

min      -7.34" nohref="" />
<area shape="rect" coords="71,244,88,197" title="max      2.42

75%      0.919207

median   -3.58317

25%      -7.99829

min      -9.47" nohref="" />
</map>
</p>

 

### <span class="SubsubsectionInline">Example 4 &mdash; omit the outer frame</span>

 This call uses options to not show an outer frame.

<p class="Input">
 <img src="HTMLFiles/climograph_12.png" alt="climograph_12.png" width="305" height="27" style="vertical-align:middle" />
</p>

<p class="Output">
 <img src="HTMLFiles/climograph_13.gif" alt="climograph_13.gif" width="360" height="489" style="vertical-align:middle;" usemap="#map_13" />
<map name="map_13">
<area shape="rect" coords="288,437,305,363" title="max      26.87

75%      22.3996

median   8.98829

25%      2.47207

min      0.3" nohref="" />
<area shape="rect" coords="268,436,285,339" title="max      35.62

75%      28.632

median   7.66805

25%      2.40451

min      0.65" nohref="" />
<area shape="rect" coords="248,437,265,294" title="max      52.6

75%      41.3405

median   7.5622

25%      2.20555

min      0.42" nohref="" />
<area shape="rect" coords="227,438,244,398" title="max      13.91

75%      11.3887

median   3.82463

25%      0.971159

min      0.02" nohref="" />
<area shape="rect" coords="207,438,224,330" title="max      39.18

75%      30.2576

median   3.49025

25%      0.872563

min      0." nohref="" />
<area shape="rect" coords="187,438,204,375" title="max      22.32

75%      17.3577

median   2.47098

25%      0.617744

min      0." nohref="" />
<area shape="rect" coords="167,438,184,355" title="max      29.82

75%      23.2235

median   3.43415

25%      0.858537

min      0." nohref="" />
<area shape="rect" coords="147,438,164,378" title="max      21.36

75%      17.0313

median   4.04537

25%      1.04884

min      0.05" nohref="" />
<area shape="rect" coords="127,436,144,399" title="max      13.2

75%      10.9637

median   4.25463

25%      1.43866

min      0.5" nohref="" />
<area shape="rect" coords="107,436,124,394" title="max      15.25

75%      12.8639

median   5.70561

25%      1.8539

min      0.57" nohref="" />
<area shape="rect" coords="87,435,103,369" title="max      24.53

75%      20.0292

median   6.52683

25%      2.41921

min      1.05" nohref="" />
<area shape="rect" coords="66,435,83,375" title="max      22.46

75%      18.7689

median   7.69561

25%      2.6964

min      1.03" nohref="" />
<area shape="rect" coords="288,234,305,195" title="max      11.3

75%      10.5556

median   8.32244

25%      5.34311

min      4.35" nohref="" />
<area shape="rect" coords="268,218,285,167" title="max      16.65

75%      15.4877

median   12.001

25%      8.61024

min      7.48" nohref="" />
<area shape="rect" coords="248,185,265,147" title="max      20.29

75%      19.3863

median   16.6751

25%      14.4363

min      13.69" nohref="" />
<area shape="rect" coords="227,161,244,126" title="max      24.32

75%      23.5584

median   21.2737

25%      18.9909

min      18.23" nohref="" />
<area shape="rect" coords="207,144,224,107" title="max      27.95

75%      27.1975

median   24.94

25%      22.4125

min      21.57" nohref="" />
<area shape="rect" coords="187,142,204,110" title="max      27.44

75%      26.7754

median   24.7815

25%      22.6129

min      21.89" nohref="" />
<area shape="rect" coords="167,152,184,122" title="max      25.16

75%      24.422

median   22.208

25%      20.462

min      19.88" nohref="" />
<area shape="rect" coords="147,182,164,149" title="max      20.05

75%      19.3579

median   17.2815

25%      15.0679

min      14.33" nohref="" />
<area shape="rect" coords="127,209,144,168" title="max      16.47

75%      15.4513

median   12.3954

25%      9.88634

min      9.05" nohref="" />
<area shape="rect" coords="107,239,124,189" title="max      12.44

75%      11.3869

median   8.22756

25%      4.65189

min      3.46" nohref="" />
<area shape="rect" coords="87,251,103,201" title="max      10.17

75%      9.17488

median   6.18951

25%      2.37238

min      1.1" nohref="" />
<area shape="rect" coords="66,239,83,206" title="max      9.09

75%      8.35823

median   6.16293

25%      4.06823

min      3.37" nohref="" />
</map>
</p>

 

### <span class="SubsubsectionInline">Example 5 &mdash; styling the inner frame</span>

 This call uses options to show the inner frame with a particular style.

<p class="Input">
 <img src="HTMLFiles/climograph_14.png" alt="climograph_14.png" width="389" height="124" style="vertical-align:middle" />
</p>

<p class="Output">
 <img src="HTMLFiles/climograph_15.gif" alt="climograph_15.gif" width="360" height="489" style="vertical-align:middle;" usemap="#map_15" />
<map name="map_15">
<area shape="rect" coords="288,438,305,409" title="max      14.52

75%      12.1074

median   4.86951

25%      1.21738

min      0." nohref="" />
<area shape="rect" coords="268,438,285,392" title="max      23.64

75%      20.1073

median   9.50927

25%      2.41482

min      0.05" nohref="" />
<area shape="rect" coords="248,434,265,294" title="max      77.98

75%      63.5479

median   20.2515

25%      6.51787

min      1.94" nohref="" />
<area shape="rect" coords="227,426,244,342" title="max      51.55

75%      44.0855

median   21.692

25%      10.1105

min      6.25" nohref="" />
<area shape="rect" coords="207,436,224,356" title="max      43.78

75%      36.8713

median   16.1454

25%      4.52384

min      0.65" nohref="" />
<area shape="rect" coords="187,432,204,360" title="max      41.27

75%      34.9505

median   15.992

25%      6.34549

min      3.13" nohref="" />
<area shape="rect" coords="167,431,184,368" title="max      36.81

75%      31.9216

median   17.2566

25%      7.14915

min      3.78" nohref="" />
<area shape="rect" coords="147,429,164,386" title="max      26.85

75%      23.672

median   14.1378

25%      7.19445

min      4.88" nohref="" />
<area shape="rect" coords="127,431,144,381" title="max      29.62

75%      25.5449

median   13.3195

25%      5.98488

min      3.54" nohref="" />
<area shape="rect" coords="107,430,124,395" title="max      22.12

75%      19.6298

median   12.159

25%      6.33226

min      4.39" nohref="" />
<area shape="rect" coords="87,436,103,379" title="max      30.78

75%      24.6499

median   6.25951

25%      2.27738

min      0.95" nohref="" />
<area shape="rect" coords="66,438,83,409" title="max      14.01

75%      11.9095

median   5.6078

25%      1.43945

min      0.05" nohref="" />
<area shape="rect" coords="288,226,305,204" title="max      10.15

75%      9.73476

median   8.48902

25%      6.91476

min      6.39" nohref="" />
<area shape="rect" coords="268,206,285,177" title="max      15.54

75%      14.9763

median   13.2851

25%      11.1663

min      10.46" nohref="" />
<area shape="rect" coords="248,174,265,155" title="max      20.09

75%      19.6998

median   18.5293

25%      17.2548

min      16.83" nohref="" />
<area shape="rect" coords="227,150,244,124" title="max      26.17

75%      25.5932

median   23.8629

25%      22.1957

min      21.64" nohref="" />
<area shape="rect" coords="207,141,224,107" title="max      29.63

75%      29.0795

median   27.4278

25%      24.437

min      23.44" nohref="" />
<area shape="rect" coords="187,146,204,112" title="max      28.58

75%      27.9216

median   25.9466

25%      23.3016

min      22.42" nohref="" />
<area shape="rect" coords="167,157,184,136" title="max      23.8

75%      23.4147

median   22.2588

25%      20.7672

min      20.27" nohref="" />
<area shape="rect" coords="147,172,164,149" title="max      21.15

75%      20.6621

median   19.1983

25%      17.7521

min      17.27" nohref="" />
<area shape="rect" coords="127,200,144,169" title="max      17.2

75%      16.5792

median   14.7168

25%      12.4542

min      11.7" nohref="" />
<area shape="rect" coords="107,229,124,194" title="max      12.21

75%      11.5502

median   9.57098

25%      6.81024

min      5.89" nohref="" />
<area shape="rect" coords="87,243,103,212" title="max      8.62

75%      8.09939

median   6.53756

25%      3.90689

min      3.03" nohref="" />
<area shape="rect" coords="66,239,83,215" title="max      8.04

75%      7.52299

median   5.97195

25%      4.29049

min      3.73" nohref="" />
</map>
</p>

<div style="font-family:Helvetica; font-size:11px; width:100%; border:1px none #999999; border-top-style:solid; padding-top:2px; margin-top:20px;">
 <a href="http://www.wolfram.com/language/" style="color:#000; text-decoration:none;">
  <span style="color:#555555">Created with the Wolfram Language</span> 
 </a>
</div>
