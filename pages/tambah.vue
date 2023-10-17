<template>
    <div>
        <h1>
            <h1>Isi Buku Tamu</h1>
                form @submit.prevent=“simpan()”>
                <input v-model=“nama” placeholder=“nama”> <br/>
                <input v-model=“tgl” placeholder=“instansi”> <br/>
                <textarea v-model=“alamat” placeholder=“alamat”></textarea> <br/>
                <button type=“submit”>Kirim</button>
                <NuxtLink to=“/“>Kembali</NuxtLink>
            </form>
        </h1>
    </div>
</template>