<template>
  <div class="container">
    <form>
      <h1>Aplikasi Bantuan Di Era Pandemi</h1>
      <br />
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Nama</label
        >
        <div class="col-sm-10">
          <input
            type="string"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Nama Lengkap"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >NIK</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="NIK Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Nomor Kartu Keluarga</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Nomor Kartu Keluarga Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="exampleFormControlFile1"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Foto KTP</label
        >
        <div class="col-sm-10">
          <input
            type="file"
            class="form-control-file"
            id="exampleFormControlFile1"
          />
          <h6>*Maksimal 2MB, format JPG/JPEG/PNG/BMP</h6>
        </div>
      </div>
      <div class="form-group row">
        <label
          for="exampleFormControlFile1"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Foto Kartu Keluarga</label
        >
        <div class="col-sm-10">
          <input
            type="file"
            class="form-control-file"
            id="exampleFormControlFile1"
          />
          <h6>*Maksimal 2MB, format JPG/JPEG/PNG/BMP</h6>
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Umur</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Umur Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Jenis Kelamin</label
        >
        <div class="col-sm-1">
          <br />

          <div class="form-check form-check-inline-lg">
            <input
              class="form-check-input"
              type="radio"
              name="inlineRadioOptions"
              id="inlineRadio1"
              value="option1"
            />
            <label class="form-check-label" for="inlineRadio1">Pria</label>
          </div>
        </div>
        <div class="col-sm-1">
          <br />

          <div class="form-check form-check-inline-lg">
            <input
              class="form-check-input"
              type="radio"
              name="inlineRadioOptions"
              id="inlineRadio1"
              value="option1"
            />
            <label class="form-check-label" for="inlineRadio1">Wanita</label>
          </div>
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Alamat</label
        >
        <div class="col-sm-10">
          <input
            type="string"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Alamat Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >RT</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="RT Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >RW</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="RW Anda"
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Penghasilan Sebelum Pandemi</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Rp."
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Penghasilan Setelah Pandemi</label
        >
        <div class="col-sm-10">
          <input
            type="number"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Rp."
          />
        </div>
      </div>
      <div class="form-group row">
        <label
          for="colFormLabelLg"
          class="col-sm-2 col-form-label col-form-label-lg"
          >Alasan Membutuhkan Bantuan</label
        >
        <div class="col-sm-10">
          <select class="custom-select custom-select-lg mb-2">
            <option delected>Alasannya</option>
            <option value="1">Kehilangan Pekerjaan</option>
            <option value="2">Kepala Keluarga Terdampak / Korban Covid</option>
            <option value="3"
              >Tergolong Fakir/Miskin Semenjak Sebelum Covid</option
            >
          </select>
          <input
            type="string"
            class="form-control form-control-lg"
            id="colFormLabelLg"
            placeholder="Lainnya.."
          />
        </div>
      </div>
      <div class="form-group">
        <div class="form-check">
          <input
            class="form-check-input"
            type="checkbox"
            value=""
            id="invalidCheck2"
            required
          />
          <label class="form-check-label" for="invalidCheck2">
            Saya menyatakan bahwa data yang diisikan adalah benar dan siap
            mempertanggung jawabkan apabila ditemukan ketidaksesuaian dalam data
            tersebut.
          </label>
        </div>
      </div>
      <button class="btn btn-primary" type="submit">Mengirimkan Form</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Formuser",
};
</script>

<style></style>
