---
title: Audio Samples — Shared Neural Audio Decoder Across Codec Operating Points
---

# Audio Samples for "Shared Neural Audio Decoder Across Codec Operating Points"

Each row is one operating point. Columns compare:
**Official codec decode**, **Ours (Sum)**, **Ours (Concat)**.  
A single **Reference (original)** is shown once per sample.

<style>
  /* Slightly stronger, clearer tables on white backgrounds */
  .aud-wrap{
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
  }

  table.aud{
    border-collapse: collapse;
    width: auto;            /* shrink-wrap to content */
    display: inline-table;  /* avoid stretching to full container width */
    border: 2px solid #bdbdbd;
    background: #fff;
    margin: 0.5rem 0 1.25rem 0;
  }
  table.aud th, table.aud td{
    border: 1px solid #c7c7c7;
    padding: 10px;
    vertical-align: top;
  }
  table.aud th{
    background: #e9e9e9;
    border-bottom: 2px solid #bdbdbd;
    text-align: left;
  }
  table.aud tr:nth-child(even) td{
    background: #f7f7f7;
  }
  table.aud tr:hover td{
    background: #f0f0f0;
  }
  table.aud audio{
    width: 240px;
    max-width: 100%;
    display: block;
  }

  /* Make <details>/<summary> look a bit nicer */
  details{
    border: 1px solid #d0d0d0;
    border-radius: 6px;
    padding: 10px 12px;
    margin: 12px 0;
    background: #fafafa;
  }
  summary{
    cursor: pointer;
    font-size: 1.05em;
  }
</style>

---

<details open>
  <summary><strong>Sample p229_213</strong></summary>

  <p><strong>Reference (original)</strong></p>
  <audio controls preload="none" src="samples_for_website/ref/p229_213_mic1.wav"></audio>

  <h3>EnCodec (24 kHz)</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>1.5 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/1_5kbps/p229_213_mic1_dec_24Hz_1.5kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>3 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/3kbps/p229_213_mic1_dec_24Hz_3.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>6 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/6kbps/p229_213_mic1_dec_24Hz_6.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>12 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/12kbps/p229_213_mic1_dec_24Hz_12.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/24kbps/p229_213_mic1_dec_24Hz_24.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>

  <h3>DAC</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>6 kbps / 16 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/16kHz_6kbps/p229_213_mic1_dec_16000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~8 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_8kbps/p229_213_mic1_dec_44100Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~16 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_16kbps/p229_213_mic1_dec_44100Hz_16kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps / 24 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/24kHz_24kbps/p229_213_mic1_dec_24000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_sum/p229_213_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_concat/p229_213_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>
</details>

---

<details>
  <summary><strong>Sample p232_121</strong></summary>

  <p><strong>Reference (original)</strong></p>
  <audio controls preload="none" src="samples_for_website/ref/p232_121_mic1.wav"></audio>

  <h3>EnCodec (24 kHz)</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>1.5 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/1_5kbps/p232_121_mic1_dec_24Hz_1.5kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>3 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/3kbps/p232_121_mic1_dec_24Hz_3.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>6 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/6kbps/p232_121_mic1_dec_24Hz_6.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>12 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/12kbps/p232_121_mic1_dec_24Hz_12.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/24kbps/p232_121_mic1_dec_24Hz_24.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>

  <h3>DAC</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>6 kbps / 16 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/16kHz_6kbps/p232_121_mic1_dec_16000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~8 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_8kbps/p232_121_mic1_dec_44100Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~16 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_16kbps/p232_121_mic1_dec_44100Hz_16kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps / 24 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/24kHz_24kbps/p232_121_mic1_dec_24000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_sum/p232_121_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_concat/p232_121_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>
</details>

---

<details>
  <summary><strong>Sample p238_003</strong></summary>

  <p><strong>Reference (original)</strong></p>
  <audio controls preload="none" src="samples_for_website/ref/p238_003_mic1.wav"></audio>

  <h3>EnCodec (24 kHz)</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>1.5 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/1_5kbps/p238_003_mic1_dec_24Hz_1.5kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>3 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/3kbps/p238_003_mic1_dec_24Hz_3.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>6 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/6kbps/p238_003_mic1_dec_24Hz_6.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>12 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/12kbps/p238_003_mic1_dec_24Hz_12.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/24kbps/p238_003_mic1_dec_24Hz_24.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>

  <h3>DAC</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>6 kbps / 16 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/16kHz_6kbps/p238_003_mic1_dec_16000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~8 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_8kbps/p238_003_mic1_dec_44100Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~16 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_16kbps/p238_003_mic1_dec_44100Hz_16kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps / 24 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/24kHz_24kbps/p238_003_mic1_dec_24000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_sum/p238_003_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_concat/p238_003_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>
</details>

---

<details>
  <summary><strong>Sample p243_024</strong></summary>

  <p><strong>Reference (original)</strong></p>
  <audio controls preload="none" src="samples_for_website/ref/p243_024_mic1.wav"></audio>

  <h3>EnCodec (24 kHz)</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>1.5 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/1_5kbps/p243_024_mic1_dec_24Hz_1.5kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/1_5kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>3 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/3kbps/p243_024_mic1_dec_24Hz_3.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/3kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>6 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/6kbps/p243_024_mic1_dec_24Hz_6.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/6kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>12 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/12kbps/p243_024_mic1_dec_24Hz_12.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/12kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps</td>
        <td><audio controls preload="none" src="samples_for_website/codec/encodec/24kbps/p243_024_mic1_dec_24Hz_24.0kbits.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/encodec/24kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>

  <h3>DAC</h3>

  <div class="aud-wrap">
    <table class="aud">
      <tr>
        <th>Config</th>
        <th>Official codec decode</th>
        <th>Ours (Sum)</th>
        <th>Ours (Concat)</th>
      </tr>

      <tr>
        <td>6 kbps / 16 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/16kHz_6kbps/p243_024_mic1_dec_16000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/16kHz_6kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~8 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_8kbps/p243_024_mic1_dec_44100Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_8kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>~16 kbps / 44.1 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/44.1kHz_16kbps/p243_024_mic1_dec_44100Hz_16kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/44.1kHz_16kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>

      <tr>
        <td>24 kbps / 24 kHz</td>
        <td><audio controls preload="none" src="samples_for_website/codec/dac/24kHz_24kbps/p243_024_mic1_dec_24000Hz_8kbps.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_sum/p243_024_mic1.wav"></audio></td>
        <td><audio controls preload="none" src="samples_for_website/ours/dac/24kHz_24kbps_concat/p243_024_mic1.wav"></audio></td>
      </tr>
    </table>
  </div>
</details>

---

## Licensing

Audio excerpts are taken from the **CSTR VCTK Corpus (v0.92)** (University of Edinburgh, CSTR), available at **doi:10.7488/ds/2645**, and are used under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

**Changes:** excerpts clipped for presentation; reference audio may be resampled to match codec operating points; additional “codec” and “ours” files are algorithmic reconstructions derived from the original recordings.

This project is not affiliated with the dataset creators.