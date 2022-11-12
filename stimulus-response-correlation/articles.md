# Review on Stimulus and Brain Response Correlation Research Work

## SRC Metric
<table>
<thead>
  <tr>
    <th>Paper Title</th>
    <th>Year</th>
    <th>Modality</th>
    <th>Stimulus</th>
    <th>Audio Features</th>
  </tr>
</thead>
  
<tbody>
<tr>
  <td>
    <a href = 'https://ccrma.stanford.edu/groups/meri/assets/pdf/gang2017preprint.pdf'>
      Decoding Neurally Relevant Musical Features Using Canonical Correlation Analysis</a></td>
  <td>2017, ISMIR</td>
  <td>EEG</td>
  <td>NMED-H (16 stimuli)<br> 4 bollywood songs, each:
    <ul>
      <li>Intact</li>
      <li>Measure Shuffled</li>
      <li>Reversed</li>
      <li>Phase Scrambled</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Zero Crossing Rate</li>
      <li>Spectral Centroid</li>
      <li>High/Low Energy Ratio</li>
      <li>Spectral Spread</li>
      <li>Spectral Roll-off</li>
      <li>Spectral Entropy</li>
      <li>Spectral Flatness</li>
      <li>Roughness</li>
      <li>RMS Energy</li>
      <li>Broadband Spectral Flux</li>
      <li>10 Sub-Band Spectral Flux</li>
    </ul></td>
</tr>

<tr>
  <td><a href = 'https://doi.org/10.1016/j.neuroimage.2020.116559'>
    Natural Music Evokes Correlated EEG Responses Reflecting Temporal Structure And Beat</a></td>
  <td>2020, Elsevier</td>
  <td>EEG</td>
  <td>NMED-H (16 stimuli)<br> 4 bollywood songs, each:
    <ul>
      <li>Intact</li>
      <li>Measure Shuffled</li>
      <li>Reversed</li>
      <li>Phase Scrambled</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Beat Onset Times</li>
      <li>Measure Boundary Times</li>
      <li>Stimulus Envelope</li>
      <li>Magnitude Envelope Fluctuations</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'https://dx.plos.org/10.1371/journal.pone.0141281'>
    Multi-Variate EEG Analysis As A Novel Tool To Examine Brain Responses To Naturalistic Music Stimuli</a></td>
  <td>2015, PLOS ONE</td>
  <td>EEG</td>
  <td>
    <ul>
        <li>Simple Tone Sequences</li>
        <li>Full-length Romantic Piano Pieces</li>
        <li>Natural (non-music) Soundscapes</li>
      </ul>
    </td>
  <td>
    <ul>
      <li>Sound intensity</li>
      <li>Sharpness</li>
      <li>Spectral Centroid</li>
      <li>Spectral entropy</li>
      <li>Spectral Flux</li>
      <li>Fluctuation Centroid</li>
      <li>Fluctuation Entropy</li>
      <li>Pulse Clarity</li>
      <li>Key Clarity</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'https://ccrma.stanford.edu/~blairbo/assets/pdf/appaji2020ISMIR_LBD.pdf'>
    Modelling Perception Of Rhythmic Complexity: Computational And Neural Measures</a></td>
  <td>2020, ISMIR</td>
  <td>EEG</td>
  <td>NMED-RP<br> 12 audio excerpts from bollywood songs:
    <ul>
      <li>Even</li>
      <li>Polyrhythm</li>
      <li>Swing</li>
      <li>Syncopated</li>
    </ul>
  </td>
  <td>Pulse Clarity</td>
</tr>

<tr>
  <td><a href = 'https://ccrma.stanford.edu/groups/meri/assets/pdf/kaneshiroDmochowski2015ISMIR.pdf'>
    Neuroimaging Methods For Music Information Retrieval: Current Findings And Future Prospects</a></td>
  <td>2015, ISMIR</td>
  <td>EEG<br>MEG<br>ECoG<br>fMRI<br>DTI</td>
  <td></td>
  <td>Acoustical features suggested by Alluri et al. <a href = 'https://pubmed.ncbi.nlm.nih.gov/22116038/'>[1]</a></td>
</tr>

<tr>
  <td><a href = 'https://www.frontiersin.org/articles/10.3389/fnhum.2017.00384/full'>
    Familiarity Affects Entrainment Of EEG In Music Listening</a></td>
  <td>2017, Frontiers</td>
  <td>EEG</td>
  <td>
    <ul>
      <li>Melodies produced by piano sounds: 20</li>
      <li>Scrambled Versions: 10</li>
    </ul>
  </td>
  <td>Amplitude Envelope</td>
</tr>

<tr>
  <td><a href = 'https://ccrma.stanford.edu/~blairbo/assets/pdf/kaneshiro2018ISMIR_LBD.pdf'>
    Evidence Of Beat Entrainment In Maximally Reliable Cortical Responses To Natural Music</a></td>
  <td>2018, ISMIR</td>
  <td>EEG</td>
  <td>NMED-T<br>10 full-length songs with electronically produced beats at various tempos</td> 
  <td>
    <ul>
      <li>Tempo</li>
      <li>Amplitude Envelope</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'http://www.nature.com/articles/s41598-018-20732-3'>
    Identifying Musical Pieces From fMRI Data Using Encoding And Decoding Models</a></td>
  <td>2018, Nature Journal</td>
  <td>fMRI</td>
  <td>40 pieces with duration of 46 s from different genres:
    <ul>
        <li>Classical Music</li>
        <li>Rock</li>
        <li>Pop</li>
        <li>Jazz</li>
        <li>Folk</li>
      </ul>
      All stimuli:
      <ul>
        <li>With lyrics</li>
        <li>Without lyrics</li>
      </ul>
    </td>
  <td>
    <ul>
      <li>ZCR</li>
      <li>Spectral centroid</li>
      <li>Brightness</li>
      <li>Spectral Spread</li>
      <li>Spectral Roll-off</li>
      <li>Spectral Entropy</li>
      <li>Spectral Flatness (Wiener entropy)</li>
      <li>Roughness</li>
      <li>RMSE</li>
      <li>10 Sub-Band Spectral Flux</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'http://dx.doi.org/10.1016/j.neuroimage.2013.11.017'>
    Capturing The Musical Brain With Lasso: Dynamic Decoding Of Musical Features From fMRI Data</a></td>
  <td>2013, Elsevier</td>
  <td>fMRI</td>
  <td>16-minute excerpt from B-side of the album Abbey Road by The Beatles (1969)</td>
  <td>Acoustic components:
    <ul>
      <li>Fullness</li>
      <li>Brightness</li>
      <li>Activity</li>
      <li>Timbral Complexity</li>
      <li>Pulse Clarity</li>
      <li>Key Clarity</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'https://royalsocietypublishing.org/doi/10.1098/rstb.2013.0393'>
    Exploring How Musical Rhythm Entrains Brain Activity With Electroencephalogram Frequency-Tagging</a></td>
  <td>2014, Philosophical Transactions, Royal Society</td>
  <td>EEG</td>
  <td>Rhythmic Patterns consisting of short sounds alternating with silences<br>i.e. acoustic sequences not strictly isochronous</td>
  <td>Frequency Spectrum of the Audio Envelope</td>
</tr>

<tr>
  <td><a href = 'https://linkinghub.elsevier.com/retrieve/pii/S1053811918300338'>
    Decoding The Auditory Brain With Canonical Component Analysis</a></td>
  <td>2018, Elsevier</td>
  <td>EEG</td>
  <td>Speech excerpts from an audiobook<br>Each approximately of duration 155s<br>Total duration approximately of 1.4 hours</td>
  <td>
    <ul>
      <li>Temporal Envelope</li>
      <li>Spectogram</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'https://ieeexplore.ieee.org/abstract/document/6334018/'>
    Analysis Of Ongoing EEG Elicited By Natural Music Stimuli Using Nonnegative Tensor Factorization</a></td>
  <td>2012, EUSIPCO</td>
  <td>EEG</td>
  <td>Entire musical piece of modern 8.5-minute tango<br>- Astor Piazzolla<br>Recorded in a concert in Lausanne, Switzerland</td>
  <td>Long-term acoustic features <a href = 'https://pubmed.ncbi.nlm.nih.gov/22116038/'>[1]</a>: <br> 
    <ul>
      <li>Mode</li>
      <li>Key Clarity</li>
      <li>Fluctuation Centroid</li>
      <li>Fluctuation Entropy</li>
      <li>Pulse Clarity</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'http://ieeexplore.ieee.org/document/6482644/'>
    Linking Brain Responses To Naturalistic Music Through Analysis Of Ongoing EEG And Stimulus Features</a></td>
  <td>2013, IEEE Transactions On Multimedia</td>
  <td>EEG</td>
  <td>Entire musical piece of modern 8.5-minute tango<br>- Astor Piazzolla<br>Recorded in a concert in Lausanne, Switzerland</td>
  <td>Tonal and rhythmic features <a href = 'https://pubmed.ncbi.nlm.nih.gov/22116038/'>[1]</a>: <br> 
    <ul>
      <li>Mode</li>
      <li>Key Clarity</li>
      <li>Fluctuation Centroid</li>
      <li>Fluctuation Entropy</li>
      <li>Pulse Clarity</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'https://doi.org/10.1016/j.jneumeth.2018.03.014'>
    On Application Of Kernel PCA For Generating Stimulus Features For fMRI During Continuous Music Listening</a></td>
  <td>Journal of Neuroscience Methods, 2018</td>
  <td>fMRI</td>
  <td>Entire musical piece of modern 8.5-minute tango<br>- Astor Piazzolla<br>Recorded in a concert in Lausanne, Switzerland</td>
  <td>
    <ul>
      <li>Fullness</li>
      <li>Brightness</li>
      <li>Activity</li>
      <li>Timbral Complexity</li>
      <li>Pulse Clarity</li>
      <li>Key Clarity</li>
      <li>Mode</li>
      <li>Rhythmic Complexity</li>
      <li>Event Synchronicity</li>
    </ul>
  </td>
</tr>

<tr>
  <td><a href = 'http://journal.frontiersin.org/article/10.3389/fpsyg.2017.01255/full'>
    Toward Studying Music Cognition With Information Retrieval Techniques: Lessons Learned From TheOpenMIIR Initiative</a></td>
  <td>Frontiers, 2017</td>
  <td>EEG, EOG</td>
  <td>12 short well-known music fragments<br>Each 7-16s long<br>
    Songs recorded: 
    <ul>
      <li>With lyrics</li>
      <li>Without lyrics</li>
      <li>Instrumental Pieces</li>
    </ul>
  </td>  
  <td>
    <ul>
      <li>Audio Envelope</li>
      <li>Tempo</li>
      <li>Meter</li>
      <li>Beat Annotations</li>
    </ul>
  </td>  
</tr>

<tr>
  <td><a href = 'https://doi.org/10.1016/j.neuroimage.2017.05.037'>
    Extracting Multidimensional Stimulus-Response Correlations Using Hybrid Encoding-Decoding Of Neural Activity</a></td>
  <td>Elsevier, 2017</td>
  <td>EEG</td>
  <td>Clip from the film: "Dog Day Afternoon"<br>Duration: 325 s</td>  
  <td>
    <ul>
      <li>Temporal Contrast</li>
      <li>Luminance</li>
      <li>Local Contrast</li>
      <li>Sound Envelope</li>
      <li>Optical Flow</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

## References

<!--[Link to Table](#table)-->

<a href = 'https://pubmed.ncbi.nlm.nih.gov/22116038/'>
  [1] Alluri, Vinoo & Toiviainen, Petri & Jääskeläinen, Iiro & Glerean, Enrico & Sams, Mikko & Brattico, Elvira. (2011). Large-scale brain networks emerge from dynamic     processing of musical timbre, key and rhythm. NeuroImage. 59. 3677-89. 10.1016/j.neuroimage.2011.11.019.</a>
